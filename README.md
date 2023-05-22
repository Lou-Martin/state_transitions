# state_transitions
State Transition Submission

1. States:

* Log-in page
* Sign-up page
* Logged-in page

2. Events:

* User signs up
* User logs in
* User logs out
* User navigates to sign up page
* User enters invalid sign up information
* User enters invalid log in information

3. Transitions:

* From the Log-in page, the "User logs in" event leads to the Logged-in page.
* From the Log-in page, the "User enters invalid log in information" event leads to the Log-in page (remains on the same page).
* From the Sign-up page, the "User signs up" event leads to the Log-in page.
* From the Sign-up page, the "User enters invalid sign up information" event leads to the Sign-up page (remains on the same page).
* From the Log-in page, the "User navigates to sign up page" event leads to the Sign-up page.
* From the Logged-in page, the "User logs out" event leads to the Log-in page.

4. State Transition Diagram:

5. State Transition Table:

6. Test Case:

Please note I have created a basic end-to-end test script.

Starting state: Log-in page

1. [ ] User navigates to the Sign-up page
2. [ ] User enters an invalid email and a weak password
3. [ ] User attempts to sign up (stays on Sign-up page due to invalid data)
4. [ ] User enters a valid email and a strong password
5. [ ] User signs up (redirected to Log-in page)
6. [ ] User is on the Log-in page
7. [ ] User enters an incorrect email or password
8. [ ] User attempts to log in (stays on Log-in page due to invalid data)
9. [ ] User enters the correct email and password used during sign-up
10. [ ] User logs in
11. [ ] User is on the Logged-in page
12. [ ] User logs out
13. [ ] User is on the Log-in page again