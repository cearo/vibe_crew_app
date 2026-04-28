# Purpose
This application is being created for the company Vibe Yoga, a small and woman owned yoga studio in Henderson, NV, to assist in organizing and scheduling Front Desk and Teaching shifts.

# Problem Statement
The process of scheduling and organizing Front Desk and Teaching shifts is a very manual process:
- The owners of the studio have to manually update a Google Sheet that serves as the scheduling calendar.
	- This sheet is not easily accessible by the employees, unless you're physically at the studio and can access the computer.
	- This sheet is entirely manually maintained.
	- This sheet tracks all scheduling needs including:
		- Front Desk Shifts
			- Scheduled Front Desk responsibilities (i.e. mopping)
		- Teaching Shifts
		- Vacations
		- Workshops/Special Classes
		- Scheduling announcements (like schedule/personnel changes)
		- Special Events (the studio's birthday, Yoga Teacher Training Graduation, etc...)
- For personnel changes, the owners of the studio have to manually text employees to see if someone is available to take the shift.
	- They then have to manually update the sheet mentioned above.
	- Employees do not have the ability or option to manually sign up for available shifts.
	- Employees must also manually text the owners to notify them if they need their position filled.
- There are no notifications for employees when their shifts are coming up.

# Features
- Multi-platform - Android, iPhone, iOS, and Windows desktop.
- User Account role-based permissions:
	- Owner
		- All permissions, including the ability to manage Administrators.
	- Administrator
		- Able to edit all lower permissions
		- Able to add/edit/remove all events
		- Approve requests
	- Teacher
		- Able to request substitute for their own class.
		- Able to sign up to substitute for another teacher.
		- Can enter vacation events
		- Can request Special Events, Announcements, Workshops/Special Classes
	- Front Desk
		- Able to request their Shift be filled by other Front Desk Employees.
		- Able to sign up to fill a Front Desk Shift.
		- Can enter vacation events.
		- Can request Special Events and Announcements.
- A visual calendar display showing the month
	- The ability to filter events based on:
		- Event type (i.e. Front Desk Shift, Teaching Shift, Vacation, etc...)
			- Certain Event Types, like Shifts, can be filtered to only show shifts available to be picked up.
		- Assigned Employee
			- Including an option for You (the signed in Employee)
	- The calendar can go out to 6 months in the future.
	- Assignable colors for Event Types.
	- Calls to action for high priority Events (i.e. Shift Available for Pickup, Announcements, etc...)
	- Monday/Week/Day views
		- Controls to shift view based on the chosen interval (i.e. shift forward or back 1 Month/Week/Day)
	- The ability to take action on a Day:
		- View/Add/Edit/Remove an Event.
- User Notifications
	- New Shift available.
	- New Announcement.
	- A Substitute/Fill has been found.
	- Your Shift is coming up.
		- Configurable notification window.
	- A Shift has been added for you.