# Perfomance Testing and Analyzing the Test reports
### Approaches 
```bash
Add Api for different types manually & (With Brazemeter)
Api Chaining With different Api
Testplan Automation,HTML Report Generation
Report Analysis and  report to managers

```

#### Description 
```bash
Test purpose e 5 or 10 thread is okay, but don't give more. And keep the ramp up within 10 sec.

You can also study 
1.Load testing
   Load testing is the process of putting simulated demand on software, an application or website in a way that tests or demonstrates it's behavior under various conditions.

2.Endurance testing
   Endurance testing simulates hundreds or even thousands of users engaging with your system at the same time

3. Spike testing
   A spike test is a type of load testing that verifies whether the system survives and performs under sudden and massive rushes of utilization

```
#### Report to PM  
```bash
Dear Sir/ma'am, 
I've completed performance test on frequently used API for Test App. 
Test executed for the below mentioned senario in server xxx.xxx.xxx.xxx
Auth	150 with 3 loop count; avg for toal sample is ~ 150 Total Api requested ~ 900 .
CreateBooking	150 3 loop count; avg for toal sample is ~ 150 Total Api requested ~ 900 .
Delete	150 3 loop count; avg for toal sample is ~ 150 Total Api requested ~ 900 .
GetBooking	150 3 loop count; avg for toal sample is ~ 150 Total Api requested ~ 900 .
PartialUpdate	150 3 loop count; avg for toal sample is ~ 150 Total Api requested ~ 900 .
UpdateBooking	150 3 loop count; avg for toal sample is ~ 150 Total Api requested ~ 900 .

While executed 900 request .fund 50 request got connection timeout and error rate is 5.89% 

##### server can handle almost concurrent 850 api call with 0% error rate 
```
