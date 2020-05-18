关联mysql失败_Server returns invalid timezone. Go to 'Advanced' tab and set 'serverTimezon'
时区错误，MySQL默认的时区是UTC时区，比北京时间晚8个小时。

所以要修改mysql的时长

在mysql的命令模式下，输入：

set global time_zone='+8:00';

再次连接成功