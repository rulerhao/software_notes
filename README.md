# Linux
## Suspend/Resume
 - /sys/power/pm_wakeup_irq is a way to know when the device wakes up.
 - - It would be possible to integrate several resources, likethe  power button/wake alarm be shown as PMIC
 - - /sys/kernel/debug/wakeup_soruces to know which one cause resume.
## Wakealarm
 - echo 0 > /sys/class/rtc/rtc0/wakealarm
 - echo $timestamp > /sys/class/rtc/rtc0/wakealarm
 - Based on RTC.
### RTC
 - hwclock
 - Pull up IRQ while up to time.
 - Set the date to the alarm register.
## Framebuffer
### W11
### Wayland

## SSD
## HDD
### Transfer time:
 - [Seek time] - Move the read/write head to the track.
 - [Rotational latency] - Move the read/write head to the desired sector.

# Android
## BLE
### Connect
 - Must wait for about 500~1000ms after scanning to prevent code 133 when connect.
