# wxMiniProgramTimer
微信小程序 计时器 倒计时 timer

创建
@param timeInterval 时间间隔 单位毫秒
@param repeat  bool是否重复执行 
@param triggered 时间间隔触发  fun(timer)
timer = new JNTimer(1000, true, function(e){

})
 
启动、停止
timer.start()
timer.stop()
