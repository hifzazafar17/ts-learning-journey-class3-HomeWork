# ts-learning-journey-class3-HomeWork
Unraveling TypeScript Mysteries: Exploring 'any,' 'unknown,' and 'never' with Sir Hamzah's Curiosity! 

**Explanation:**

**any:**
Think of any like a wildcard. It allows you to use any type of value, but it comes with a trade-off – you lose the benefits of TypeScript's type checking. It's like saying, "I'm not sure what type this will be, so let me do whatever I want with it."

**unknown:**
With unknown, you're being more cautious. It's like saying, "I don't know what type this is, and I need to be careful." Before using the value, you have to check or tell TypeScript what type it really is. It adds a layer of safety compared to any.

**never:**
This one is about things that will never happen. If a function returns never, it means it will never finish executing (like an infinite loop) or will always throw an error. It's like saying, "This should never, ever happen." It's handy for situations where a certain value is not expected.

So, in simple terms:

any is like a free pass for any type but risky.
unknown is cautious and needs confirmation.
never is for things that should never occur.
