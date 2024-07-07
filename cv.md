# Olga Surnina

![foto](mefoto.jpg "My foto")

## Contacts

_Location:_ Russia, Yoshkar-Ola

_E-mail:_ veehja88@gmail.com

_Telegram:_ @Veehja

_Tel:_ +7 999 609 9600

## About me

I am 35 years old. I'm learning frontend.
I am diligent and easy to train. 
I hope that this school will help me reach a new level of my knowledge.

## Skills

I studied such frontend topics as:
HTML, JS, BAM, WordPress, Git, VSC.

## My projects:

+ <https://olgasurnina.github.io/TravelRoom/>
+ <https://olgasurnina.github.io/Kusto/>
+ <https://github.com/OlgaSurnina/PortfolioSurnina>

## Code Example

```
"use strict"
Array.from(document.querySelectorAll('.room')).map(room => {
    room.addEventListener('click', function (e) {
        const t = e.currentTarget.querySelector('.room__reserved');
        const d = e.currentTarget.querySelector('.room__reserved-reserved');
        const i = e.currentTarget.querySelector('.room__image');

        const addClass = () => {
            t.classList.add('hidden');
            d.classList.add('visible');
            i.classList.add('room__image-reserv');
        };

        const removeClass = () => {
            t.classList.add('visible');
            t.classList.remove('hidden');
            i.classList.remove('room__image-reserv');
            d.classList.add('hidden');
            d.classList.remove('visible');
        };

        if (e.target.classList.contains('room__reserved-btn')) {
            e.currentTarget.onmouseleave = () => {
                debugger
                addClass()
            }
        }
        if (!e.target.classList.contains('room__reserved-btn')) {
            e.currentTarget.onmouseleave = () => {
                removeClass();
            }
        }
    });
});
```

## Experience

I have no experience in commercial development.

## Education

VOLGA STATE UNIVERSITY OF TECHNOLOGY'13


Specialization: social work.

## English

English level:  B1.

