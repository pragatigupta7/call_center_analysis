# call_center_analysis

Answered = CALCULATE(COUNT(Sheet1[Call Id]),FILTER(Sheet1, Sheet1[Answered (Y/N)]="Y"))

DayOfWeek = FORMAT(Sheet1[Date],"dddd")

Resolved (Y) = CALCULATE(COUNT(Sheet1[Call Id]),FILTER(Sheet1,Sheet1[Resolved]="Y"))

Average Handling time = AVERAGE(Sheet1[AvgTalkDuration])*24*60*60
