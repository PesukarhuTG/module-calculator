## Module-calculator
 ![](https://github.com/PesukarhuTG/module-calculator/blob/master/img/preview.jpg)
[Preview html page ►](https://pesukarhutg.github.io/module-calculator/)
___________________________________________________________________________

### Usage

Input data as sex, height, weight, age, ratio.<br>
* sex = famale/male (*default = female)
* height = person's height
* weight = person's weight
* age = persons's age
* ratio = min 1.2 / low 1.375 / middle 1.55 / hight 1.725 (*default = 1.375)

Data for calculating were taken from [this site](https://fitseven.ru/zdorovie/metabolism/sutochnaya-norma-kaloriy)

The total result includes the formula<br>
► for male: BMR = 88.36 + (13.4 x weight, kg) + (4.8 х height, sm) – (5.7 х age)<br>
► for female: BMR = 447.6 + (9.2 x weight, kg) + (3.1 х height, sm) – (4.3 х age)

_________________________________________________________________________
### Install
    npm install
    npm install webpack webpack-cli --save-dev
    npx webpack
