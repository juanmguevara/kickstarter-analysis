# kickstarter-analysis

### Module 1 - Performing Analysis on Kickstarter Data to Uncover Trends

Outcomes of all the categories

<img src="https://qomi1g.ch.files.1drv.com/y4mHzFLB5jhnzGb0GUMPtjM4R7izL-Lgjyyu8uevUw23q4lhaMQwqkGveMiX672HkGm-CG4Fve6jl8ytK7uwgLHVdtudKglKcOyOL90Q55PRNM0guum-XLgeN6KZSbcMeBXTeAnhM4wJX7KWQaYPdzfcC43UYqT5I-_sVQlswKRHLhoxNkUXi5tVOGXUdZlxGCJogLOzGDDrGaG1-ZZ0MhPfQ?width=769&height=527&cropmode=none" width="1569" height="527" />

- We have found that there were 525 successful theater campaigns in the United States. We can easily see which parent categories performed well and which ones did not.

Filter by subcategory. We’re using subcategories in order to focus our analysis on an area that is more relevant for Louise: theatrical productions.

<img src="https://qemj1g.ch.files.1drv.com/y4mZ3ggMudIUZeP3YPuP8UVQdA5V59aUN-Cv5225aIcU_K-8aaLYvEkctJmDyHFBNLhe_CuPJ58_XtoLKrHg8Km7WXkDPpJ2f2nbNq8wNXdtFkFMYqGuhwuEt5_iBZ3_wJz3EhgyMqxQtwyvRb-qGnkYBJt7Fhaoswm3tHehhVRCtXTfsxgOLHdKsrIDJjuDjbI6H51_pZRPw_XICD3rY5kgA?width=1583&height=1147&cropmode=none" width="1583" height="547" />

Now we know that the total number of Kickstarter campaigns is just over 4,000, and 3,038 of them are from the U.S. Let’s look at Great Britain’s statistics.

-

We have found that while there is only a total of 604 Kickstarter campaigns for plays in Great Britain, the “plays” category is the most successful.

Line charts are helpful when trying to determine trends. We can see by looking at our new chart that the months of May and June both have a greater success rate.

<img src="https://qomj1g.ch.files.1drv.com/y4m4STXxLR4LWOAlckZElDO-nvsujJB4XOTWU-yM56beVUYQITcBHP0LlprEEPVoVu456xGWslKH1vpT4yAVyMl1tSlfQNSpzNaE0-PFn6YnoLlhHJmy2MAQPPVu01mIvvDVgC72PjPim3CjeYQU92_DgWDAb1e5O0Ne34jRF3GPyPY-y_2GF-UE5D62_8h7ZmQlH-_iVt8P4wP5iHIHPVE_w?width=718&height=438&cropmode=none" width="1569" height="438" />

The most successful Kickstarter campaigns were started in May. On the other hand, December doesn’t seem like a great time to launch a campaign.

statistics to our analysis: standard deviation and variance.

<img src="https://qemd1g.ch.files.1drv.com/y4m8aJG0867ieFohCfwipPcUAsHlvBkvYs8GTZ1ulocm4QsUl-hTxnhFwtFLCh1cMFZ4YuCUF7-K9bzy2fbbMTJubRx4PYhcdzdKq83bCB6CV-QZ824GhRlR80ZM3e8IjHydKdFuYo1pJrnnyqlrKePcSXExZ5gtD4YlRL4DwF1elEFMJXiVWl1js0gB7fb0nI7HQurADr0fPj3Q-DlKKBfmQ?width=574&height=416&cropmode=none" width="574" height="416" />

Based on these statistics, we can determine the following:
-	The mean of each distribution is around the 3rd quartile, so the data follows similar distributions in each subset.
-	The standard deviations are larger than the mean, which means everything below the mean is considered “close” to the center.
-	Some large values are driving all of these distributions. The standard deviations are all roughly twice the IQR in each distribution, except in the failed Kickstarters, where the standard deviation is closer to three times the IQR. There must be some failed Kickstarters with really high goals!

Louise mentioned earlier that she’s also interested in Great Britain’s theater market, especially musicals. While she’s committed to creating a play in the U.S., she’s also interested in researching musicals in Great Britain for a future project with an estimated budget of £4,000.

<img src="https://qemc1g.ch.files.1drv.com/y4mfcPtgUIuOfaA0thBBtYpxt4v1Ys7cKEJQaqWnrb_UXfxpTfadB3bJMlvYEYIKMsQUTyRHIcyIqsBKRFUyPIKgriuVE8s5-gwygqbthNLozIPQcJO04fRTR2aaaxt0zgMrYxvu-E9Dxm2h_CqiOgrWHZ4kCIzRT6qMTHepm3A7HrHgxNuo5F_ed6MgDSaWtnV3dSLQ04HbKshEPjuZYHedQ?width=1420&height=1029&cropmode=none" width="1420" height="529" />

From these plots, we can see that the mean campaign goal is around £4,000. This is outside of the range of outliers for amount pledged, so Louise should probably try to get her play produced for less than £4,000. Half of the campaign goals are less than £2,000, which is just over the 3rd quartile for amounts pledged.

---

### Challenge

<img src="https://qomg1g.ch.files.1drv.com/y4m_tLSpZeZN27166X2dydfbXxtG8roVmSlT11g4b0ZtnNFoNPBxP4B5GgV69Qz1AW0HXbWVBAbUcQ4OThPjihi7ubp1bp0j6rxphVoLev01LtTzFKjDRqi0paFWiuiwBz8xU1No-5n2eoSzqhXTl7LSOXRQdfyuCr-IAS28xill7X71B8IBDD33jFOdtoS3u4V-k62odCdVOeNEacqlz1Zjw?width=1352&height=710&cropmode=none" width="1352" height="510" />

After reviewing the data, I can conclude that Kickstarter campaigns which had a goal ranging from $1,000 to $4,999 were 73% successful with fulfilling their campaign goal. In total there was 534 campaigns with this goal and 388 of them succeeded. This goal range had the second heights success rate but considering that there were more projects done at this range and keeping a high success rate makes it the most plausible goal to achieve for a campaign regarding plays.

<img src="https://qomh1g.ch.files.1drv.com/y4mf12XFmsQgbF7piFJOQpm9Y4I7xjVwRvNoIWVuM-SKjqSIyv2CaRDrT70uqp_vTXnb-PQtX5z7lIhs1oMF50hEXYlrTdcCDS8CiQTAIT5-lTzn0EXHNSH0r7IcBagF-Nv2tKGONUREk_Uxq-54Khzm80KB8v7xoqIqmzq5garBMMi2pjKvLb4hPXHtaPc5ya4ITgID4fQpu5hBlJD-QuOlw?width=1119&height=640&cropmode=none" width="1119" height="540" />

The length of a campaign might not determine the ultimate success or failure, but the month at which the campaign chooses to start can greatly affect its success or failure. In example, as seen on the graph for Outcomes Based on Launch Date you will see the month of May having the most successes totaling to 111 campaigns succeeding and 52 failing. This gives the month of May a 67% rate of success. In addition to that after furthering my analysis of average donations given each month we can see that the Month of May had the heights total sums of donations happen. This coincides with the high success rate happing. 

<img src="https://qome1g.ch.files.1drv.com/y4myDiAuvPVqPpEu9fjWNeEZ5xqPEwRQIQ0tivgYEYXtTaNbLNlvlFt9Buv7D2nRxcVSUCjyR-ERvAF6NNakf-OQQ8XbH3FgVi3IpPCBA9UbLwuNPVD7w3AzoKvYMuht1jtQmx6D9ug5IoX2OUVFWeJ-YQ73MEqTgbt8PTpEF4onUW5GG3lJwIrPc3CfxFBbXRjInvnhsj2RKrCGxyYEfBjDw?width=820&height=569&cropmode=none" width="820" height="569" />

Subsequently, the time at which the campaign chooses to start can contribute to its ultimate success or failure. I would advise to start your campaign at during May or Jun. With a preference in May, given that it has the highest success rate and June because it has the second highest success rate for campaigns with Plays.
