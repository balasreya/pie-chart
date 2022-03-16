# pie-chart
states<-c("andhrapradesh","telangana","up","mp","goa")
print("enter population in 2019")
population1<-scan()
india<-data.frame(states,population1)
print(india)
pie(population1,
    labels=states,
    main="population in south india 2019",
    col=rainbow(length(states)))
