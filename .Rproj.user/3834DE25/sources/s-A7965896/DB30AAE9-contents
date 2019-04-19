for (h in 1:length(list.files(pattern = "week"))) {
  
  print(list.files(pattern = "week")[h])
  
}

h <- 1

repeat {
  
  unzip(list.files(pattern = "week")[h])
  
  h <- h+1
  
  if (h > length(list.files(pattern = "week"))) {
    break
  }
  
}

View(summarise(group_by(ASX_Data_Frame, ASX_Ticker),
          "n" = n()))

View(arrange(ASX_Data_Frame, ASX_Ticker, Date))

distinct(ASX_Data_Frame)

max(ymd(ASX_Data_Frame$Date)) - min(ymd(ASX_Data_Frame$Date))

dmy("12-04-2019") - dmy("02-01-2019")

