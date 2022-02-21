---
name: User Story
about: POS Summary Screen needed at checkout
title: ''
labels: ''
assignees: ''

---

**As a** [Store Clerk using POS at a car yard]  
 **I need** [A summary screen]  
 **So that** [I can see a list at checkout showing quantity totals of the rang up car parts, warranty, and core charges in my order in one screen]  
   
 ### Details and Assumptions
 * [A button will be added called Checkout Summary that will enable a Pop up summary screen over the POS Sales screen revealing on the bottom subtotals from the POS screen. 
*[Button will be positioned between the Restart Transaction and Continue to Payment button ]

   
 ### Acceptance Criteria  
   
 ```gherkin
 Given [a list of rang up car parts are not all visible on the POS screen without scrolling]
 When [I click on the Checkout Summary button]
 Then [A Pop up screen showing a list of: description of part, quantity total, core charges, warranty type and cost of warranty, Part(s) total charges]
