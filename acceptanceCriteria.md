# TC001 – Product Subscription
**Environment:** Local  

**Test type:** Feature  

**Feature/Working area:** Product Subscription  

**Tags/Group:** @Regression  

**Test case objective:** Validate the product price for a full special support plan for 6 months simulation  

**Preconditions:** 
* None  

**Target:**  

| Browser               |
|:----------------------|
| **Browser type**: Google Chrome |
    
### Actions
#### 1. Calculate the price of a full special support plan for 6 months
* **Expected Result:** Price is 2249.10$
* **Steps:**
    <ol>
        <li>Select type "Special"</li>
        <li>Select support plan "Full"</li>
        <li>Choose a duration of 6 months</li>
        <li>Click the "Calculate" button</li>
    </ol>
           
### Test case data 
| Item                  | Value      |
|:----------------------|:-----------|
| URL                   |  https://qa-automation-challenge.github.io/sandbox/ |