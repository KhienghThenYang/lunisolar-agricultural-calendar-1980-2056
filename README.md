# lunisolar-agricultural-calendar-1980-2056
https://github.com/infinet/lunar-calendar

## iCalendar 格式的农历 节气 及传统节日

iCalendar 是一种通用的日历交换格式，很多软件和设备，比如 google calendar, apple
calendar, thunderbird + lightning 插件, iphone/ipad, 安卓都支持。

以前订过 iCalendar 格式农历日历，但慢慢地它们都停止了更新。所幸香港天文台为公众提
供了从 1901 年到 2100 年间两百年的农历-公历对照表，也就是这里用到的数据。

下面是覆盖去年、今年以及明年三年的日历 [ics文件][iCal] 链接，把它加入到你最常用的
软件就可以了。

[https://raw.github.com/KhienghThenYang/lunisolar-agricultural-calendar-1980-2056/master/chinese_lunar_1980_2056.ics][iCal]

苹果设备上应该是:
    设置 => 邮件、通讯录、日历 => 添加账户 => 其它 => 日历 添加已订阅日历

如果在 Mac 的 *iCal* 里订阅到 iCloud，这个日历还可以自动推送到所有使用那个 iCloud
账户的 ios 备。

以香港天文台的数据(更新于 2014 年)为标准，用此法生成的 1949 到 2100 年间农历有两处不一致：

 1）1979-01-20 大寒

 2）2057-09-29 农历九月全部日期错位一天

不一致的原因在于上面两处节气及新月正好跨越午夜时分，差距数秒就能影响该节气或新月的
发生日期。由于使用不同的行星位置计算方法和 Delta T 估算方法，出现这种差异在所难免。

[iCal]: https://raw.github.com/KhienghThenYang/lunisolar-agricultural-calendar-1980-2056/master/chinese_lunar_1980_2056.ics
