<h2>Loging Authentication Limits</h2>

test Case ID : Login-1	<br>
Test Senario : Authentication Limits <br>
Third time fail login 3 minute delay <br>
prerequisition : login fail 2 time	 <br>
test condition : login in Third time fail 3 minute delay <br>


| No |     Action    |    Inputs   | Expected Output  |   Actual output   | 
| -- | ------------- | ----------- | ---------------- | ----------------- |
| 1 | login#1 | username + Password | username or password fail | username or password fail |
| 2 | login#2 | username + Password | username or password fail | username or password fail |
| 3 | login#3 | username + Password | username or password fail and delay refresh page 3  minute | username or password fail and delay refresh page 3  minute |
| 4 | login#4 | username + Password | username or password fail and delay refresh page 3  minute | username or password fail | 


<br>
Members <br>
- Nantawan Sanpukdee <br>
- Supattra Boonkied <br>
