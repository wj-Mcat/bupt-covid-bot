# bupt-covid-bot

![](./assets/imgs/badge.png)

> Image from [Voice-bot for Telecom](https://medium.com/arnekt-ai/voice-bot-for-telecom-b96ffa89e3b)

## 为什么要做这个机器人？

学校为了实时监控全校师生的健康状态，每日的健康打卡是非常有必要的，可是健康打卡存在以下问题：

- 在家/在校学生可能会由于私人原因忘记打卡，此时只能够由导员或班长通过在系统中查看哪些学生没有打卡，然后挨个儿私聊提醒。
- 学校会有很多个微信群，每个导员和班长会每天都会定时查看监控后台（即使有私事也必须要完成此工作）查看未打卡成员，然后挨个儿提醒。
- 很多时候提醒不仅仅是一次，而是多次反复的提醒，这就大大增加了导员和班长的工作量，毕竟管理的学生可能会非常多。
- 作为国内顶尖的计算机领域高等院校，使用软件实现自动化管的工作理应该要走在前列，所以ChatOps这个工具我想还是很有必要开始使用起来。
- 作为学生+聊天机器人爱好者而言，深感这个项目如果做好，会很大程度上减少学校内部的沟通成本和人力成本。
- ...

## Features

- 每天自动提醒群内成员的打卡情况
- 根据打卡系统内部的接口来私聊每个学生以及老师来提醒打卡
- 每个群内成员都对应学校某一个年级/班级/部门等，通过不同纬度来统计和提醒对应学生和老师
- 聊天机器人拥有高度可定制化的可能，能够编写出所有复杂场景下的自动化管理业务

## 技术可行性

- 本人是北邮人工智能学院一名研二学生，研究方向是聊天机器人，同时也是[python-wechaty](https://github.com/wechaty/python-wechaty)开源项目的作者，具备开发聊天机器人的能力。
- 上述属于定制化业务聊天机器人，没有任何技术上的壁垒，故理论上是可行的。
- 打开系统接口开放情况需要与校内技术人员沟通，在不接触到学生敏感信息的情况下是否可以开放接口，或者源代码让校内技术人员运维都是可以的。

## Creators

- [@wj-Mcat](https://github.com/wj-Mcat) - Jingjing WU (吴京京)
- [Gmail](wjmcater@gmail.com)
- 微信号:pure-_--love

## Copyright & License

- Code & Docs © 2020 吴京京 <https://github.com/wj-Mcat>
- Code released under the Apache-2.0 License
- Docs released under Creative Commons