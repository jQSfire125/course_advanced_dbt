# Bingeflix Docs
This file contains documentation for Bingeflix data sources.

## General
This section is for documentation that on the Bingeflix source.

{% docs bingeflix_data_source%}
This source contains tables from the Bingeflix production database
{% enddocs %}



## Users
This section contains documentation from the Bingeflix users table.

{% docs bingeflix_users_table%}
This is table contains information about Bingeflix users.
{% enddocs %}

{% docs bingeflix_user_id %}
The unique identifier of the user.
{% enddocs %}

{% docs bingeflix_user_created_at %}
When the user was created.
{% enddocs %}

{% docs bingeflix_phone_number %}
The user's phone number.
{% enddocs %}

{% docs bingeflix_user_deleted_at %}
When the user's account was deleted. The value is NULL if the account has not been deleted.
{% enddocs %}

{% docs bingeflix_username %}
The username for login to Bingeflix.
{% enddocs %}

{% docs bingeflix_name %}
The full name of the user (first and last).
{% enddocs %}

{% docs bingeflix_sex %}
The user's sex at birth.
{% enddocs %}

{% docs bingeflix_email %}
The user's email address.
{% enddocs %}

{% docs bingeflix_birthdate %}
The user's birthdate.
{% enddocs %}

{% docs bingeflix_current_age %}
The user's current age.
{% enddocs %}

{% docs bingeflix_age_at_acquisition %}
The age of the user when they became a Bingeflix user.
{% enddocs %}

{% docs bingeflix_region %}
Where the user resides (i.e. the state or province).
{% enddocs %}

{% docs bingeflix_country %}
Where the user resides.
{% enddocs %}

{% docs bingeflix_first_subscription_starts_at %}
Where the user's first subscription started
{% enddocs %}

{% docs bingeflix_count_of_subscriptions %}
How many subscriptions the user has.
{% enddocs %}


## Subscriptions
This section contains documentation from the Bingeflix subscriptions table.

{% docs bingeflix_subscriptions_table%}
This table contains information about Bingeflix subscriptions.
{% enddocs %}

{% docs bingeflix_subscription_plan_id%}
The unique identifier of the subscription plan.
{% enddocs %}

{% docs bingeflix_starts_at%}
When the subscription started.
{% enddocs %}

{% docs bingeflix_ends_at%}
When the subscription plan ends (The value is NULL if the subscription plan has auto-renew turned on/does not have a defined end date).
{% enddocs %}

{% docs bingeflix_subscription_id%}
The unique identifier for the subscription.
{% enddocs %}


## Subscription Plans
This section contains documentation from the Bingeflix subscription plans table.

{% docs bingeflix_subscription_plans_table%}
This table contains information about various subscription plans available on Bingeflix.
{% enddocs %}

{% docs bingeflix_subscription_plan_name%}
The name of the subscription plan.
{% enddocs %}

{% docs bingeflix_subscription_plan_pricing%}
The price of the subscription plan per payment period.
{% enddocs %}

{% docs bingeflix_subscription_plan_payment_period%}
The cadence of the payment period for the subscription plan (e.g., monthly, annually).
{% enddocs %}


## Events
This section contains documentation from the Bingeflix events table.

{% docs bingeflix_events_table%}
This table contains information about the behavioral events of users while they interact with the Bingeflix platform.
{% enddocs %}

{% docs bingeflix_session_id%}
The unique identifier of the session in the Bingeflix application.
{% enddocs %}

{% docs bingeflix_event_created_at%}
When the event was logged.
{% enddocs %}

{% docs bingeflix_event_name%}
The name of the event.
{% enddocs %}

{% docs bingeflix_event_id%}
The unique identifier of the event.
{% enddocs %}
