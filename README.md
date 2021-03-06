# yii2-zoom

[![GitHub tag](https://img.shields.io/badge/license-BSD%203--Clause-brightgreen.svg)]()
[![GitHub tag](https://img.shields.io/badge/tag-v1.0.0-brightgreen.svg)]()
[![GitHub tag](https://img.shields.io/badge/composer-yii2--extension-orange.svg)]()
[![GitHub tag](https://img.shields.io/badge/tests-8%20tests%2C%2039%20assertions-yellowgreen.svg)]()

## What is zoom?

> Zoom unifies cloud video conferencing, simple online meetings, group messaging, and a software-defined conference room solution into one easy-to-use platform. Our solution offers the best video, audio, and wireless screen-sharing experience across Windows, Mac, iOS, Android, Blackberry, Linux, Zoom Rooms, and H.323/SIP room systems. Founded in 2011, Zoom's mission is to develop a people-centric cloud service that transforms the real-time collaboration experience and improves the quality and effectiveness of communications forever. 

> Official website [https://zoom.us/](https://zoom.us/)

## Install
`composer require x1ankun/yii2-zoom v1.1.0 -vvv`

## Configuration
```
//zoom应用组件
'zoom' => [
    'class' => 'x1ankun\Zoom\ZoomApi',
    "api_key" => "",
    "api_secret" => "",
    "data_type" => "JSON"
]
```

## Usage example
```
//创建zoom用户
$zoom = Yii::$app->zoom;
$resource = $zoom->createUser('test1101@test.com');        
```
