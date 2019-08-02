flume日志采集清洗日志文件
 
1.查看文件日志：

`cd /var/log/flume/flume-cmf-flume-AGENT-linux6.log`

`tail -n -100 flume-cmf-flume-AGENT-linux6.log`

2.部分日志文件：

[![flume.log文件](index_files/9bdedfbc-1be9-4d49-9946-4e18bbaf2f3d.png "flume.log文件")](file:///C:/Users/Administrator/Documents/My%20Knowledge/temp/f878a635-22bb-497f-83aa-54e28d48d954/128/index_files/9bdedfbc-1be9-4d49-9946-4e18bbaf2f3d.png "flume.log文件")


[![flume.log部分数据采集](index_files/3bda30b4-ee16-467b-91dc-393dfb5d0620.png "flume.log部分数据采集")](file:///C:/Users/Administrator/Documents/My%20Knowledge/temp/f878a635-22bb-497f-83aa-54e28d48d954/128/index_files/3bda30b4-ee16-467b-91dc-393dfb5d0620.png "flume.log部分数据采集")
    

  //  "table":"mail"
    {"mail_content":"","mail_type":"","latitude":"63.887339","imsi":"27459272283248","phone_mac":"Dc-tp-WO-SD-ho-tu","device_mac":"wo-bP-ui-Sa-oM-Xx","send_time":"1526023107","filename":"mail_source0_1111111.txt","absolute_filename":"/usr/chl/data/filedir_successful/2019-08-03/data/filedir/mail_source0_1111111.txt","device_number":"26154475","imei":"033089877228341","send_mail":"85swzvjalef@gmail.com","collect_time":"1522006645","accept_mail":"a7j23ywq9e7b@yahoo.com","id":"f05e687d1a0e42ee850782e21e57217f","accept_time":"1535813464","table":"mail","longitude":"30.416625"}到kafka成功


    //  "table":"qq"
    2019-08-03 03:10:39,527 INFO com.uestc.bigdata.kafka.producer.StringProducer: 发送数据{"latitude":"80.794781","imsi":"8222970622","accept_message":"","phone_mac":"bM-tQ-TN-BK-al-PY","device_mac":"QH-vA-ao-bp-OY-CG","message_time":"1524234999","filename":"qq_source0_32132131.txt","phone":"13805520815","absolute_filename":"/usr/chl/data/filedir_successful/2019-08-03/data/filedir/qq_source0_32132131.txt","device_number":"79944551","imei":"0078292301","collect_time":"1533145553","id":"ab3a55c80e1c46d4b7f7550f97d790a3","send_message":"","object_username":"扈妹","table":"qq","longitude":"63.469433","username":"濮莺"}到kafka成功
 

 //  "table":"wechat"
    发送数据{"latitude":"0.133824","imsi":"2574863532","accept_message":"","phone_mac":"xp-UN-Pk-gQ-FX-bH","device_mac":"iD-Hh-Yb-my-TI-DK","message_time":"1515665913","filename":"wechat_source0_32132130.txt","phone":"15905114827","absolute_filename":"/usr/chl/data/filedir_successful/2019-08-03/data/filedir/wechat_source0_32132130.txt","device_number":"19623005","imei":"7196220656","collect_time":"1539274920","id":"ab317942e76646798df8327624e13f61","send_message":"","object_username":"uXAe","table":"wechat","longitude":"31.625780","username":"iRoVLJaI"}到kafka成功    
