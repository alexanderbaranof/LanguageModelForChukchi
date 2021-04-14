# Models results


| author           | Method                               | Clicks per token (dev set) | Clicks per character (dev set) | Clicks per token (test set) | Clicks per character(test set) |
| ---------------- | ------------------------------------ | -------------------------- | ------------------------------ | --------------------------- | ------------------------------ |
| nicklogin        | Baseline(Bigrams)                    | 4.2961                     | 0.9962                         | 4.5101                      | 0.9958                         |
| nicklogin        | MorphLSTM                            | 4.0250                     | 0.9334                         | 4.4612                      | 0.9850                         |
| nicklogin        | MorphLSTM (with frequency threshold) | 4.0436                     | 0.9377                         | 4.4501                      | 0.9825                         |
| nicklogin        | CNN1D (token convolution)            | 4.1252                     | 0.9566                         | 4.4583                      | 0.9844                         |
| nicklogin        | CNN1D (embedding convolution)        | 4.0776                     | 0.9456                         | 4.4622                      | 0.9852                         |
| alexanderbaranof | Positional                           | 4.2913                     | 0.9951                         | 4.5081                      | 0.9953                         |
| alexanderbaranof | PositiomalBigrams                    | 4.2891                     | 0.9946                         | 4.4998                      | 0.9935                         |
| alexanderbaranof | CharRNN                              | 4.2930                     | 0.9955                         | It can't be counted         | It can't be counted            |
| alexanderbaranof | Word level LSTM + FastText           | 4.2960                     | 0.9962                         | 4.5180                      | 0.9975                         |
| alexanderbaranof | Token-level-language-model           | 4.2958                     | 0.9975                         | 4.5272                      | 0.9995                         |