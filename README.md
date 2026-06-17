# DLSF
DLS Fucker  

> 悩めど悩めど答えは得られず、  
> ならば咲かせよ刹那に飾る花。

![](/pics/1.webp)



## Install
```
git clone https://github.com/Ltfjx/DLSF.git
cd DLSF
npm install
```

## Start
```
npm run start
```

## Tips
新增了换课的功能，用于在你想选的某个课程的某个老师没有名额时，可以先选另一个老师，同时对你想选的老师进行检测，当出现空闲名额时，会自动退掉已经选择的班级，并选择你想选的班级。

使用方法：输入课程编号，选课序号和已经选择的课程的选课序号即可，后面两个是可选的，如果不输入会执行默认的抢课模式

注意：当你想选的课程出现空闲名额时，在退掉原课程的这个时间窗口可能会有人抢走了这个名额，此时会触发回退机制，抢回你原来的课，但是有非常非常非常非常低的概率会出现你原来的课程也被抢走。

## Use DLSF in command-line
[https://github.com/Ltfjx/DLSF-cli](https://github.com/Ltfjx/DLSF-cli)

## Termux Support
```
pkg install nodejs
pkg install git
git clone https://github.com/Ltfjx/DLSF.git
cd DLSF
npm install
npm run start
```

## PWA Support
You can install DLSF as a PWA on your Android device.  

## License
GPL  

## Disclaimer
**仅供学习交流使用，严禁用于一切违法及盈利倒卖行为。**  
