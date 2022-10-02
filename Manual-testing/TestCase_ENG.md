# Test case template 
**TEST - _Test title_**

**TEST ENVIRONMENT**

**TEST APPS AND DEVICES**

**TEST CONDITIONS**

**TEST DATA**

**TEST STEPS**

**EXPECTED RESULT**

**ACTUAL RESULT**

**SUMMARY**

**TEST RESULT**

**ATTACHEMENTS**

=====================================

## Sample test case based on www.wikipedia.org

**TEST - _ looking for test data through search box "Search Wikipedia"_**

**TEST ENVIRONMENT**
  - https://en.wikipedia.org/

**TEST APPS AND DEVICES**
  - Browser Google Chrome v. 106

**TEST CONDITIONS**:
  - User has internet access

**TEST DATA**:
  - Search word: "Software testing"

**TEST STEPS**:
  1. Open browser
  2. Open Wikipedia site
  3. In search box type test data

**EXPECTED RESULT**:
  - User is sent to article titled "Software testing"
  - Expected URL address is https://en.wikipedia.org/wiki/Software_testing

**ACTUAL RESULT**:

TC1 - Typing "Software testing" in search box
  - User is sent to article titled "Software testing"
  - URL address matches expected result

TC2 - Typing data only with small letters ("software testing") in search box
  - Użytkownik zostaje przeniesiony na podstronę "Testowanie oprogramowania"
  - Adres URL podstrony jest zgodny z oczekiwanym rezultatem

TC3 - Typing data only with capital letters ("SOFTWARE TESTING") in search box
  - Użytkownik zostaje przeniesiony na podstronę "Testowanie oprogramowania"
  - Adres URL podstrony jest zgodny z oczekiwanym rezultatem

**SUMMARY**:
  - Verification of "Search Wikipedia" search box completed with expected results.
  
**TEST RESULT**:
  - **Test passed**

**ATTACHEMENTS**:

![tc_input_wikipedia](https://user-images.githubusercontent.com/72787034/193466758-413b20a6-31e0-44dc-b137-379488838891.PNG)