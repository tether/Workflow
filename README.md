# [PetroFeed](http://petrofeed.com) Workflow

> An easy to follow and lightweight process for developing focused products in a startup environment.

#### Building a successful product is all about running tons of little experiments as quickly as possible and adjusting to the found results.

## The Process

1. Choose & Challenge.
2. Understand.
3. Create.
4. Deploy.
5. Review.

## Step by step description

### 1. CHOOSE & CHALLENGE.

- Decide what the next product improvement is (feature, stability/performance improvement, tech debt, etc).
- Verify that this product improvement provides value for the people who use your product. Especially if this is a feature focused on a specific target audience.
    - Challenge the reason to put scarce resources into it.
- Verify that **NOW** is the proper time to implement this improvement.
    - Challenge the reason to put scarce resources into it at this very moment.

### 2. UNDERSTAND.

To get everyone on the same page, have the whole team or the feature team collaboratively produce the following items:

1. Rough sketch of the feature's full interface.
2. High level technical requirements.
3. Estimated deadline. (This could be one sprint if your team is using Agile Methodology.)
4. Hypothesis for what this improvement will do. For example:
    - _This new feature will increase geologist signups by 10%._
    - _This new architecture will reduce load time down to 100ms_
    - _This refactoring will reduce the time to add notifications by half_
5. The measurables for this product enhancement:
    - _Measure the amount of geologists that click the main page signup button complete their profile_
    - _Measure the time to load all assets when someone hits the home page_
    - _Measure how long it takes to add a notification vs. how long it used to take_

Post these items somewhere for the team to see easily. Don't bury them in some obscure spot in your software. We post these items in our GitHub Pull Requests.

### 3. CREATE.

- Understand how this feature fits into your current product's architecture. **Don't just hack it in**. Decide on the best way for this new logic to fit into your product gracefully.
    - Consider technical debt or bugs that may be impeding the progress of the improvement.
    - Ensure to build in a way to track progress against your measurables from step 2.

- As a team go on and **CRUSH** your enhancement using whatever strategies you like best.

- Write automated tests for your brand spanking new improvement. (Make sure they all pass :smile:)

- Ensure that you don't skip over the creation of engagement material. _You can build a great product but if you don't tell anyone, it doesn't matter_. Engagement material might be:
    - Email campaign
    - Social media campaign
    - Website update
    - Blog post
    - Explanatory Video
    - Help Docs

- As you build things out...
    - Write down the major challenges your team faced
    - What you had to sacrifice
    - What you might have done differently
    - What went well
    - etc.

### 4. DEPLOY.

- Launch the feature into production (This should be quick and easy).
    - The feature should be fully tested and everything should be green before being deployed.

- Write a (very) small post-mortem report containing everything you've tracked for this feature from steps 1 through 3.

### 5. REVIEW.

- After 2 weeks, measure the enhancement's performance:
    - How did your hypothesis fair?
    - How do your measurables stack up?
    - Based on actual feedback, did it provide worthwile value to people using your product?
    - How did it hold up against the company's quality standards?
    - What other things are worth noting about this feature?

- Update your post-mortem report with the answers to the above questions.

- Present about this feature to a group of people outside of your team.
