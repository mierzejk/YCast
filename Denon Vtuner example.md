https://blog.webernetz.net/yamaha-r-n500-network-receiver-packet-capture/

Tcpdumps of AVR-1713. Reason for dumps: If Denon ever discontinues the vtuner service I need to serve my receiver these dumps:

Press Favorite Station 1 long to save current station as favorite.

Entrance link ```http://denon.vtuner.com:80/setupapp/denon/asp/browsexm2/navXML.asp?rLev=&gofile=web&mac=xxxxxxxxxxxxxxxxxx&fver=xxxxxx&dlang=ger&startitems=1&enditems=10```

```
<?xml version="1.0" encoding="UTF-8" standalone="yes" ?>^M
<ListOfItems>^M
<ItemCount>3</ItemCount>^M
<NoDataCache>Yes</NoDataCache>^M
<Item>^M
<ItemType>Previous</ItemType>^M
<UrlPrevious>http://denon.vtuner.com/setupapp/denon/asp/browsexm2/loginXML.asp?rLev=&amp;gofile=</UrlPrevious>^M
<UrlPreviousBackUp>http://denon.vtuner.com/setupapp/denon/asp/browsexm2/loginXML.asp?rLev=&amp;gofile=</UrlPreviousBackUp>^M
</Item>^M
<Item>^M
<ItemType>Dir</ItemType>^M
<Title>Favoriten</Title>^M
<UrlDir>http://denon.vtuner.com/setupapp/denon/asp/browsexm2/FavXML.asp?empty=</UrlDir>^M
<UrlDirBackUp>http://denon2.vtuner.com/setupapp/denon/asp/browsexm2/FavXML.asp?empty=</UrlDirBackUp>^M
</Item>^M
<Item>^M
<ItemType>Dir</ItemType>^M
<Title>HinzugefÃ¼gte Radiostationen</Title>^M
<UrlDir>http://denon.vtuner.com/setupapp/denon/asp/browsexm2/AFavXML.asp?empty=</UrlDir>^M
<UrlDirBackUp>http://denon2.vtuner.com/setupapp/denon/asp/browsexm2/AFavXML.asp?empty=</UrlDirBackUp>^M
</Item>^M
<Item>^M
<ItemType>Display</ItemType>^M
<Display>ID# 0005CD2C9CA8</Display>^M
</Item>^M
</ListOfItems>
```

Radio Stations (AFav) ```http://denon.vtuner.com:80/setupapp/denon/asp/browsexm2/AFavXML.asp?empty=&mac=xxxxxxxxxxxxxxxxxx&fver=xxxxxx&dlang=ger&startitems=1&enditems=10```
```
<?xml version="1.0" encoding="UTF-8" standalone="yes" ?>^M
<ListOfItems>^M
<ItemCount>1</ItemCount>^M
<Item>^M
<ItemType>Previous</ItemType>^M
<UrlPrevious>http://denon.vtuner.com/setupapp/denon/asp/browsexm2/loginXML.asp?gofile=</UrlPrevious>^M
<UrlPreviousBackUp>http://denon2.vtuner.com/setupapp/denon/asp/browsexm2/loginXML.asp?gofile=</UrlPreviousBackUp>^M
</Item>^M
<Item>^M
<ItemType>Station</ItemType>^M
<StationId>333001</StationId>^M
<StationName>Name1</StationName>^M
<StationUrl>http://server:8000/link.mp3</StationUrl>^M
<StationDesc></StationDesc>^M
<StationFormat>Text1</StationFormat>^M
<StationLocation>Text2</StationLocation>^M
<StationBandWidth>256</StationBandWidth>^M
<StationMime>MP3</StationMime>^M
<Bookmark>http://denon.vtuner.com/setupapp/denon/asp/browsexm2/AddFav.asp?empty=&amp;stationid=NO</Bookmark>^M
</Item>^M
</ListOfItems>
```

Favorits ```http://denon.vtuner.com:80/setupapp/denon/asp/browsexm2/FavXML.asp?empty=&mac=xxxxxxxxxxxxxxxxxx&fver=xxxxxx&dlang=ger&startitems=1&enditems=10```

empty:

```
<?xml version="1.0" encoding="UTF-8" standalone="yes" ?>^M
<ListOfItems>^M
<ItemCount>1</ItemCount>^M
<Item>^M
<ItemType>Previous</ItemType>^M
<UrlPrevious>http://denon.vtuner.com/setupapp/denon/asp/browsexm2/loginXML.asp?gofile=</UrlPrevious>^M
<UrlPreviousBackUp>http://denon2.vtuner.com/setupapp/denon/asp/browsexm2/loginXML.asp?gofile=</UrlPreviousBackUp>^M
</Item>^M
<Item>^M
<ItemType>Display</ItemType>^M
<Display>No Favorite Groups</Display>^M
</Item>^M
</ListOfItems>
```



with subdir:

```
<?xml version="1.0" encoding="UTF-8" standalone="yes" ?>^M
<ListOfItems>^M
<ItemCount>1</ItemCount>^M
<Item>^M
<ItemType>Previous</ItemType>^M
<UrlPrevious>http://denon.vtuner.com/setupapp/denon/asp/browsexm2/loginXML.asp?gofile=</UrlPrevious>^M
<UrlPreviousBackUp>http://denon2.vtuner.com/setupapp/denon/asp/browsexm2/loginXML.asp?gofile=</UrlPreviousBackUp>^M
</Item>^M
<Item>^M
<ItemType>Dir</ItemType>^M
<Title>Jo</Title>^M
<UrlDir>http://denon.vtuner.com/setupapp/denon/asp/browsexm2/FavXML.asp?empty=&amp;sFavName=SubdirName</UrlDir>^M
<UrlDirBackUp>http://denon2.vtuner.com/setupapp/denon/asp/browsexm2/FavXML.asp?empty=&amp;sFavName=SubdirName</UrlDirBackUp>^M
</Item>^M
</ListOfItems>
```

Favorits subdir ```http://denon.vtuner.com:80/setupapp/denon/asp/browsexm2/FavXML.asp?empty=&sFavName=SubdirName&mac=xxxxxxxxxxxxxxxxxx&fver=xxxxxx&dlang=ger&startitems=1&enditems=10```

```
<?xml version="1.0" encoding="UTF-8" standalone="yes" ?>^M
<ListOfItems>^M
<ItemCount>1</ItemCount>^M
<Item>^M
<ItemType>Previous</ItemType>^M
<UrlPrevious>http://denon.vtuner.com/setupapp/denon/asp/browsexm2/FavXML.asp?empty=gofile=</UrlPrevious>^M
<UrlPreviousBackUp>http://denon2.vtuner.com/setupapp/denon/asp/browsexm2/FavXML.asp?empty=gofile=</UrlPreviousBackUp>^M
</Item>^M
<Item>^M
<ItemType>Station</ItemType>^M
<StationId>28875</StationId>^M
<StationName>egoFM 104.0</StationName>^M
<StationUrl>http://denon.vtuner.com/setupapp/denon/asp/func/dynamOD.asp?ex45v=8B577C5FD651B408DFBA942CA014CE88&amp;id=28875</StationUrl>^M
<StationDesc>Wir spielen die richtig gute Musik aus allen Bereichen, am liebsten Elektro, Urban Soul und deutsche Poesie. Wir mögen alles, was unabhängig ist.</StationDesc>^M
<Logo>http://logo.vtuner.net/007452/logo/logo-28875.jpg</Logo>^M
<StationFormat>Variety</StationFormat>^M
<StationLocation>Germany</StationLocation>^M
<StationBandWidth>128</StationBandWidth>^M
<StationMime>MP3</StationMime>^M
<Bookmark>http://denon.vtuner.com/setupapp/denon/asp/browsexm2/RemoveFavs.asp?empty=&amp;ID=28875&amp;ShowID=0&amp;sFavName=Jo</Bookmark>^M
</Item>^M
</ListOfItems>
```
