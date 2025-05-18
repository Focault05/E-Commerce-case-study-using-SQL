# E-Commerce-case-study-using-SQL
--- 1. find top 3 outlets by cuisine type without using limit and top function
- By knowing top outlets for each cuisine, Noon foods can give special offers or discounts to increase the number of orders.
- Other outlets can perform better by knowing their competitors.
- Customers will spend less time in searching a good outlet to place order.

--- 2. find the daily new customer count starting from the launch date( everyday how many new customers are we acquiring)
- Business growth metric.
- Analysis like this will help Noon foods to find patterns and seasonality.
- Also helps in finding out the effectiveness of marketing campaigns.
- Tracking new users helps you distinguish between acquisition vs. retention metrics.
- If new users are growing but overall users are flat, it may indicate you're losing existing users.

  --- 3. Count of all the users who were acquired in Jan 2025 ,only placed one order in Jan and did not placed any order further.
  -  Evaluates Customer Experience & Product Fit like one-time users might reflect:
   1.Poor product satisfaction
   2.Pricing issues
   3.Bad delivery experience
   4.Ineffective onboarding
- Analyzing this group helps you in finding out where the experience breaks down.

  --- 4. List all customers with no order in last 7 days but were acquired one month ago with their first order on promo.
  -  Evaluates Promotional Effectiveness: whether your promotions are driving long-term customer value or just one-time transactions.
  -  Boosts **Customer Lifetime Value (CLTV)**
  -  These users can form a segment for **A/B testing**:
     1. Promo follow-up offers
     2. Surveys to understand why they didn’t return
     3.Different onboarding flows


--- 5.growth team is planning to create a trigger that will target customers after their evry third order with a personalised communication and they have asked you to create a query for this.
- Helps track purchase frequency.
- Encourages repeat purchases through targeted nudges.
- Builds automated communication pipelines based on behavioral triggers.
- Supports the marketing team with relevant user segmentation for campaigns.

--- 6. List all customers who placed more than 1 order and all their orders on a promo code only
- Helps in understanding which segment is price-sensitive.
- Marketing teams can decide whether to retain these users or shift focus to more profitable segments.
- Design Better Promo Strategies(personalised).
  
--- 7.  what % of customers were organically acquired in Jan 2025( placed their first order without using promo code)
- If organic growth is strong, you might scale it more with content, community, or referral programs rather than just promo-based campaigns.
- Share of organic customers reflects the brand value, lower- acquisition cost, genuine interest in the product.
- This metric can help in identifying which channels are working well without promo spend( eg: SEO, word of mouth, social networking sites etc)
 
 -- 𝗞𝗲𝘆 𝗟𝗲𝗮𝗿𝗻𝗶𝗻𝗴𝘀:
- ✅ 𝑫𝒂𝒕𝒂 𝑹𝒆𝒕𝒓𝒊𝒆𝒗𝒂𝒍: SELECT, WHERE, DISTINCT, LIKE
- ✅ 𝑺𝒐𝒓𝒕𝒊𝒏𝒈 & 𝑭𝒊𝒍𝒕𝒆𝒓𝒊𝒏𝒈: GROUP BY, ORDER BY, LIMIT, OFFSET
- ✅ 𝑨𝒈𝒈𝒓𝒆𝒈𝒂𝒕𝒊𝒐𝒏 𝑭𝒖𝒏𝒄𝒕𝒊𝒐𝒏𝒔: SUM, COUNT, MIN, MAX, AVG, GROUP BY, HAVING
- ✅ 𝑼𝒏𝒗𝒆𝒊𝒍𝒊𝒏𝒈 𝑹𝒆𝒍𝒂𝒕𝒊𝒐𝒏𝒔𝒉𝒊𝒑𝒔: JOINS, Subqueries, Correlated Subqueries
- ✅ 𝑨𝒅𝒗𝒂𝒏𝒄𝒆𝒅 𝑨𝒏𝒂𝒍𝒚𝒕𝒊𝒄𝒔: CASE, YEAR, CURYEAR, IF, CTEs, User Defined Functions, Windows Functions
- ✅ 𝑫𝒂𝒕𝒂𝒃𝒂𝒔𝒆 𝑴𝒂𝒏𝒂𝒈𝒆𝒎𝒆𝒏𝒕: DDL, DML, Data Types, Views.
