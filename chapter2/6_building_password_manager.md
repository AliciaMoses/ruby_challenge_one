# Password Manager

In this chapter we covered everything you need in order to build the password manager. Now it's time to put everything into practice.

## Before You Begin

Do the drills for this chapter to get practice with each individual component before bringing everything together.
## Requirements

The password manager will need to:
- Allow you add new, validated, passwords
- Allow you to view a specific password
- Allow you to see a list of all the services for which a password has been stored

## Problem Decomposition

- You're going to need three methods:
  - `add_password`, which is used to add a new password
  - `password_for`, which returns the password for a given service
  - `all_services`, which returns a list of all the services for which a password has been stored
- The passwords will be stored in hash, where the key is the service and the value is the password
- This hash will need to be stored in an instance variable

## Getting Started

<!-- OMITTED -->


<!-- BEGIN GENERATED SECTION DO NOT EDIT -->

---

**How was this resource?**  
[😫](https://airtable.com/shrUJ3t7KLMqVRFKR?prefill_Repository=makersacademy/ruby_foundations&prefill_File=chapter2/6_building_password_manager.md&prefill_Sentiment=😫) [😕](https://airtable.com/shrUJ3t7KLMqVRFKR?prefill_Repository=makersacademy/ruby_foundations&prefill_File=chapter2/6_building_password_manager.md&prefill_Sentiment=😕) [😐](https://airtable.com/shrUJ3t7KLMqVRFKR?prefill_Repository=makersacademy/ruby_foundations&prefill_File=chapter2/6_building_password_manager.md&prefill_Sentiment=😐) [🙂](https://airtable.com/shrUJ3t7KLMqVRFKR?prefill_Repository=makersacademy/ruby_foundations&prefill_File=chapter2/6_building_password_manager.md&prefill_Sentiment=🙂) [😀](https://airtable.com/shrUJ3t7KLMqVRFKR?prefill_Repository=makersacademy/ruby_foundations&prefill_File=chapter2/6_building_password_manager.md&prefill_Sentiment=😀)  
Click an emoji to tell us.

<!-- END GENERATED SECTION DO NOT EDIT -->
