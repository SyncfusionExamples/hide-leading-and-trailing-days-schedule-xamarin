# How to hide leading and trailing days in Xamarin.Forms Schedule (SfSchedule)

You can hide the leading and trailing days the current month by using the [PreviousMonthTextColor](https://help.syncfusion.com/cr/xamarin/Syncfusion.SfSchedule.XForms.MonthViewCellStyle.html#Syncfusion_SfSchedule_XForms_MonthViewCellStyle_PreviousMonthTextColor) and [NextMonthTextColor](https://help.syncfusion.com/cr/xamarin/Syncfusion.SfSchedule.XForms.MonthViewCellStyle.html#Syncfusion_SfSchedule_XForms_MonthViewCellStyle_NextMonthTextColor) properties of [MonthViewCellStyle](https://help.syncfusion.com/cr/xamarin/Syncfusion.SfSchedule.XForms.MonthViewCellStyle.html) in Xamarin.Forms [SfSchedule](https://www.syncfusion.com/xamarin-ui-controls/xamarin-scheduler).

**XAML**

You can set Transparent to `PreviousMonthTextColor` and `NextMonthTextColor` to hide the leading and trailing days.
```
<syncfusion:SfSchedule x:Name="Schedule" ScheduleView="MonthView">
        <syncfusion:SfSchedule.MonthCellStyle>
            <syncfusion:MonthViewCellStyle PreviousMonthTextColor="Transparent" 
                                                                  NextMonthTextColor="Transparent"/>
        </syncfusion:SfSchedule.MonthCellStyle>
 </syncfusion:SfSchedule>
```

KB article - [How to hide leading and trailing days in Xamarin.Forms Schedule (SfSchedule)](https://www.syncfusion.com/kb/12229/how-to-hide-leading-and-trailing-days-in-xamarin-forms-schedule-sfschedule)
