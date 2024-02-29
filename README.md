# Перенос стилей изображений

Идея - написать модель, которая способна передать стиль одного изображения на другое.
      
За идеей нет большого смылса, она банальная, но мне кажется должно быть интересно попробовать:
  
- Написать свою собственную простую VAE модель
- При успешном выполнении первого этапа, использовать GAN модель
- Если вдруг, то обучить собственный GAN
- Написать Telegram-бота, который принимает два изображения и возвращает одно из них с перенесенным стилем.

Не слишком много таких проектов уже было?

## Ссылки

Проект хочу реализовать с использованием следующего стека технологий:

- Основные статьи - <a href="https://arxiv.org/abs/1508.06576">A Neural Algorithm of Artistic Style</a>, <a href="https://arxiv.org/abs/1703.07511">Deep Photo Style Transfer</a>
- VAE - MSG-Net <a href="https://arxiv.org/abs/1703.06953">(ссылка)</a>
- GANы - CycleGan <a href="https://arxiv.org/abs/1609.04802">(статья)</a>, CycleGANBlog <a href="https://hardikbansal.github.io/CycleGANBlog/">(github.io)</a>, 
- StyleFlow - <a href="https://arxiv.org/abs/2207.01909">(статья)</a>
- Библиотека pyTelegramBotAPI для разработки Telegram-бота - <a href="https://github.com/eternnoir/pyTelegramBotAPI/">GitHub</a>


## Датасеты

Первично, пока хочу использовать следующие датасеты:

- COCO <a href="https://www.kaggle.com/datasets/awsaf49/coco-2017-dataset">(Kaggle)</a>
- WikiArt <a href="https://huggingface.co/datasets/huggan/wikiart">(Hugging Face)</a>


## Обзор

TODO

## Лицензирование

Задавайте вопросы в телеграмм - @vsweatherfield, на почту - voff.smirnoff@gmail.com