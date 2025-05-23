# Рекуррентные нейронные сети. Трансформер

На этой неделе мы разговариваем про задачу Seq2seq, обсуждаем, как устроены RNN, в чем их преимущества и в чем заключается их недостатки при решении Seq2seq. Так же мы разбираем модель Трансформер, которая сегодня в разных вариациях применяется во всех задачах NLP и не только. В конце обсуждаются метрики для Seq2seq и способы декодирования текста (сэмплирования токенов из предсказанного распределения).


## Статьи по теме

1. LSTM: [оригинальная статья](https://www.bioinf.jku.at/publications/older/2604.pdf), [блог пост](https://colah.github.io/posts/2015-08-Understanding-LSTMs/).
1. Механизм внимания: [первая статья](https://arxiv.org/abs/1409.0473), [улучшение той же идеи](https://arxiv.org/abs/1508.04025)
1. Трансформер: [статья](https://arxiv.org/abs/1706.03762), [блогпост с подробными иллюстрациями](https://jalammar.github.io/illustrated-transformer/), [запись лекции от Андрея Карпатого](https://www.youtube.com/watch?v=XfpMkf4rD6E&ab_channel=StanfordOnline)
1. Влияние методов декодирования текста на качество: [отличная статья](https://arxiv.org/abs/1904.09751)


Разбор домашнего задания: [запись](https://disk.yandex.ru/i/6P0b_faFWPBwTQ)
