## Am I exposing an internal identifier value to the user?
- [ ] No
- [ ] Yes, and I am making sure the user is both identified and is authorized to view or work with the item

## Am I verifying the parameters that I receive to ensure that I only get expected values?
- [ ] Yes
- [ ] No, and I understand that there is a risk of receiving multiple identifer values in the payload. 

## Do I need to expose an internal identifier to the user?
- [ ] No, I am able to use a proxy value or hashed identifier value instead
- [ ] Yes, exposing the actual internal identifier is required for a business or compliance purpose and I am making sure that the user is authorized to view or work on the item.

## Am I only handling the expected HTTP methods for my service?
- [ ] Yes, I have ensured that only the specified HTTP verbs are processed and that non-allowed verbs are rejected
- [ ] No, I understand that an attacker may send unexpected HTTP verbs to my endpoint.

