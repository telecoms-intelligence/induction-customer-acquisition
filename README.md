
# Data
## Fields
* ``num_campaigns_looked``: voucher offers (e.g., 20% on Amazon purchases),
  which consumers can choose as alternative to bank payout, as campaigns.
  The field shows the number of distinct campaigns viewed by a consumer.
* ``num_campaign_poages_looked``: the total number of times a customer has seen the campaign
* ``video_viewed``: whether the tutorial video has been watched
* ``mpj``: ID generated when a customer visits the platform after clicking the link in
  the invitation message
* Outcome type
  + ``Fallback``: customer has not completed the checkout.
  The payment has been disbursed automatically after four days
  + ``Payout``: customer has completed the checkout and chosen bank transfer as payout method
  + ``Combination``: customer has completed checkout and chosen a combination
    of bank transfer and vouchers as payout method
  + ``Voucher``: customer has completed the checkout and voucher as payout method

# Use Cases
## Drop in the conversion rate

