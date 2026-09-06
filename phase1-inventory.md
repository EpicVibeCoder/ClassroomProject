# Phase 1: Attack Surface Inventory

## 1. Endpoint Catalog


| File                       | Needs login? | What it does                        |
| -------------------------- | ------------ | ----------------------------------- |
| index.php                  | No           | Login page                          |
| signup.php                 | No           | Sign up page                        |
| useraccount.php            | Yes          | User account page                   |
| twoFactor.php              | Partial      | Enter 2FA code after password login |
| classRoomBookings.php      | Yes          | Book a classroom                    |
| seatBookings.php           | Yes          | Book a seat                         |
| genqrcode.php              | Yes          | Enable 2FA / QR code                |
| signupValidation.php       | No           | Create account (API)                |
| check.php                  | Partial      | Verify 2FA code (API)               |
| logout.php                 | Yes          | Log out                             |
| getTableData.php           | Yes          | Load classroom data (API)           |
| getSeatsTableData.php      | Yes          | Load seat data (API)                |
| insertClassRoomBooking.php | Yes          | Create classroom booking (API)      |
| insertSeatBookings.php     | Yes          | Create seat booking (API)           |
| DeleteClassRoom.php        | Yes          | Delete classroom booking (API)      |
| DeleteSeats.php            | Yes          | Delete seat booking (API)           |
| updatePassword.php         | Yes          | Change password                     |
| resetPassword.php          | No           | Reset password page                 |




## 2. Data Stores



## 3. Secrets & Sensitive Files



## 4. Trust Boundaries



## 5. Threat Scenarios

