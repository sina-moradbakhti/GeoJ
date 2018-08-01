# GeoJ
convert gregorian date to jalali(shamsi) date

Using this class is very Simple.

you can define a new Object of "GeoJ" Class and use "getJalaliDate" function, that's it.
for example:

let GeoJObject = GeoJ(yearNumber: 2018, monthNumber: 08, dayNumber: 01)
let jalaliDate:String = GeoJObject.getJalaliDate()

or

let GeoJObject = GeoJ(date: "08/01/2018", delimiter: .dash, label: .mdY)
let jalaliDate:String = GeoJObject.getJalaliDate()
