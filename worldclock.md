## Simple World Clock

**Project Description**: 
This app simply displays different timezone clocks on a single page.

useState and useEffect are used to achieve this. The parent component ClockDashBoard calls the child component, CityTime, to format and update the time constantly.

CityTime makes use of setInterval and clearInterval to update the time every one second.

The overall state is managed in the variables time and setTime.

The logic works by taking the system timezone function of different cities from an array of objects
and displaying them on a frontend component.
