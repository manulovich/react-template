# Зачем эта папка? Что в ней

_smart компоненты_ - это те компоненты, которые могут использовать относительно серьезную логику, для отображения чего-либо
1. Могут использовать локальное хранилище, как и обращаться к глобальному (не изменяя его)
2. Могут использовать все доступные хуки, кроме тех, что взаимодействуют с сетью
3. Могут использовать в своей реализации Ordinary, Simple и UI компоненты.