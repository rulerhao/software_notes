# Linux
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
