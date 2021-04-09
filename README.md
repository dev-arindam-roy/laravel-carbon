> # **Useful Laravel Carbon Functions**

```
    Namespace: use Carbon\Carbon;
    
    Carbon::now();
    Carbon::now()->format('d/m/Y');
    Carbon::now()->format('d/m/Y h:i:s A');
    Carbon::today();
    Carbon::tomorrow();
    Carbon::yesterday();  
```

```
    $dt = Carbon::now();

    $dt->isFuture();
    $dt->isPast();
    $dt->isCurrentYear();
    $dt->isNextYear();
    $dt->isLastYear();
    $dt->isLongYear();
    $dt->isLeapYear();
    $dt->isCurrentQuarter();
    $dt->isNextQuarter();
    $dt->isLastQuarter();
    $dt->isCurrentMonth();
    $dt->isNextMonth();
    $dt->isLastMonth();
    $dt->isWeekday();
    $dt->isWeekend();
    $dt->isMonday();
    $dt->isTuesday();
    $dt->isWednesday();
    $dt->isThursday();
    $dt->isFriday();
    $dt->isSaturday();
    $dt->isSunday();
    $dt->isDayOfWeek(Carbon::SATURDAY);
    $dt->isLastOfMonth();
    $dt->is('Sunday');
    $dt->is('June');
    $dt->is('2019');
    $dt->is('12:23');
    $dt->is('2 June 2019');
    $dt->is('06-02');
    $dt->isCurrentDay();
    $dt->isYesterday();
    $dt->isToday();
    $dt->isTomorrow();
    $dt->isNextWeek();
    $dt->isLastWeek();
    $dt->isCurrentHour();
    $dt->isCurrentSecond();
    $dt->isStartOfDay(); 
    $dt->isMidnight();
    $dt->isEndOfDay();
    $dt->isMidday();
```

```
    $dt = Carbon::now();
    
    $dt->startOfDay();     
    $dt->endOfDay();       
    $dt->startOfMonth();   
    $dt->endOfMonth();     
    $dt->startOfYear();    
    $dt->endOfYear();      
    $dt->startOfDecade();  
    $dt->endOfDecade();    
    $dt->startOfCentury(); 
    $dt->endOfCentury();   
    $dt->startOfWeek();    
    $dt->endOfWeek();
```

