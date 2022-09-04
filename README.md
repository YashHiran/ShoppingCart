## Problem Statement

### Shopping cart:
#### 1. Adding items to empty cart
- Given: Empty shopping cart
- When: adding 3 dove soaps of 30 rupees to the cart
- Then: the total cart value is 90 rupees

#### 2. Adding items to non-empty cart
- Given: Shopping cart with 3 dove soaps of 30 rupees each
- When: adding 2 jim-jam biscuits of 50 rupees each
- Then: the total cart value is 190 rupees

#### 3. Buy one get one free offer
- Given: Empty shopping cart
- When: adding 2 oreo biscuits of rupees 50 each
- AND: there is an offer BUY ONE GET ONE free
- Then: the total cart value is 50 rupees

#### 4. Buy one get one free offer without extra free quantity
- Given: Empty shopping cart
- When: adding 1 oreo biscuits of rupees 50 each
- AND: there is an offer BUY ONE GET ONE free
- Then: the total cart value is 50 rupees

#### 5. BUY TWO GET 30% off on next
- Given: adding 1 oreo biscuits of rupees 50 each with BUY ONE GET ONE free offer
- When: adding 3 DoveShampoo bottles of rupees 100 each
- AND: there is an offer BUY TWO GET 30% off on next
- Then: the total cart value is 320 rupees

#### 6. 10% off on total cart price
- Given: Empty shopping cart
- When: adding 5 surf clothes wash for 100 each
- AND: there is an offer when cart prices is crossing 499 rupees, 10% off on total cart price
- Then: the total cart value is 450 rupees