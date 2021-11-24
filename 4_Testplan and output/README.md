# High Level Test Plan
| Test ID |	Description |	Input |	Expected output |	 Output |
| ------- | ----------- | ----- | --------------- | ------- |
| 01 |	Check voters id | 2018btecs00064 | voterfound(<100) |		(not found)
| 02 |	Check Ileegal voting |	2018btecs00064 | Repeated voting(same id repadted) |		not found
| 03| 	Check Admin panel |	3 | password |		login

# Low Level Test Plan
| Test ID |	Description |	Input |		Actual Output |
| ------- | ----------- | ----- | --------------- | 
| 01 |	Check voters id	| 2018btecs0006 (user id) |	 voter found |
| 02 | Check Ileegal voting   | 2018btecs00064 |	 illegaly voted |
| 03 |	Check Admin panel  | 3	 |	password | 
| 04 | Check voters panel  | 2 | enter user id	 |
| 05 | Check exit |	0  |	logout sucessfully  |
