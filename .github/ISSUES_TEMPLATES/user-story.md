**As a** customer  
**I need** a dashboard that displays the status of my orders and estimated delivery dates  
**So that** I can plan my schedule accordingly and be prepared to receive my orders  

### Details and Assumptions
* The dashboard should include filters for order status (e.g., processing, shipped, delivered).
* Assume that order status updates are available via API integration with our logistics provider.

### Acceptance Criteria
```gherkin
Given I am logged into my account
When I navigate to the orders dashboard
Then I should see a list of my orders with their current status
And I should see estimated delivery dates for each order
