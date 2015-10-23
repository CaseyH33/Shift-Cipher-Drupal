Shift Cipher

A site to encode text.

By Casey Heitz

Description
This is a site to encode user inputted text.  The user inputs a string, the direction of the cipher (left or right), and an integer for the shift amount.  The encoded text will then be returned to the user.  For instance, if the inputted string is "hello", the shift direction is "right", and shift amount is 3, the encoded text returned will be "khoor".

Setup
-Clone the repository from GitHub
-Open MAMP, direct the path to the root project folder, and start the servers
-Go to localhost:8888/phpmyadmin
-Select Import->Choose File, then select the database casey_cipher.sql.zip in sites/db-backup, and click Go
-Under Privileges, select Add User and add the database user listed below
-Open the site in your browser from your localhost

Database Information:
Database name: casey_cipher
Database user: epicodus
Password: epicodus

Admin user: epicodus
Password: epicodus

Technologies Used
Drupal 7.41

Legal

Copyright (c) 2015 Casey Heitz

This software is licensed under the MIT license.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
