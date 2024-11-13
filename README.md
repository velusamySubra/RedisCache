This repo provides steps to,
#1 : install and configure open source redis cluster in a on-prem linux server
#2 : use C# application to connect to redis and cache data 


Best Practises ,
1. This is simple implementaion when you go for entrerpirse level caching this can be written as a common assembly so that multiple application can use common code base.
2. If your team is looking for support rfom redis team, use redis enterprise version instead on open source

   Tools,
  #1: If an user want to see the objects visaully,  is available ffrom command prompt using redis-cli or use a desktop version of redis dashboard , its a simple exe which installs on windows/linux/Mac os where you can map redis server (serverip:port#)
   that shows actual objects in a ui, like this ,...
   #2: Datalog provide similar feature as well.

