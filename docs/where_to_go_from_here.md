Designing a scalable, fault-tolerant and high-performance system is no small feat. Here are a few tips:

1. Lambda reserved and provisioned concurrency.

2. Lambda failed destinations, dead-letter queue, invisible window, reporting batch item failures.

3. Does the ordering of messages matter?

4. Do all events go to the same SNS queue, or different queues because they are high volume?

5. Lambda has a maximum timeout of 15 minutes. Does your task take longer than that? Do you need other solutions like Docker to process your tasks?