# Ideas-and-thoughts

Chained and trained - A Risk-Based Sourcing Recommendation Tool

## Summary
This tool helps reduce supplier risks by recommending tailored supply chain strategies for each component or product, based on simulated probabilities of global events such as strikes, tariffs, and natural disasters. Users can adjust risk assessments based on their priorities, including ethical considerations and delivery reliability, while sub-suppliers can update their own status. The main goal is to identify the most suitable sourcing strategy for each product, focusing on supplier-side risk management rather than customer-facing challenges.

## Background

## 1. Which problems does your idea solve?

- **Reducing supply chain risks:** The tool identifies risks associated with components, suppliers, and sub-suppliers to reduce the likelihood and impact of production disruptions.
- **Improving supplier selection:** It recommends the most suitable sourcing strategy based on known risks, potential costs, and the company's risk aversion.
- **Improving communication and trust:** By enabling suppliers and sub-suppliers to update their status and share relevant information, the tool aims to improve communication and strengthen supplier relationships.
- **Encouraging proactive risk management:** The tool helps companies implement Supply Chain Risk Management (SCRM) by considering risks throughout the supply chain, rather than focusing only on direct suppliers.
- **Supporting more resilient supply chains:** It can help companies evaluate alternatives such as local suppliers, multiple sourcing options, and suppliers with similar working conditions to reduce transportation risks and other vulnerabilities.

## 2. How common or frequent is this problem?

Supply chain disruptions are a recurring challenge for manufacturing companies that depend on external suppliers and globally distributed supply chains. Events such as natural disasters, geopolitical conflicts, strikes, tariffs, and transportation disruptions can delay deliveries and cause production stoppages. Even a disruption at a single sub-supplier can affect the entire supply chain, leading to significant financial losses. The frequency and impact vary between industries and companies, but the potential consequences make systematic risk management important.

## 3. What is your personal motivation?

My motivation comes from analysing supplier risks and sourcing strategies in a manufacturing context as part of a university project. Through this work, I saw how dependent production can be on individual components and suppliers, and how different sourcing strategies involve trade-offs between cost and risk. I want to develop a practical tool that makes this type of analysis more accessible and helps companies make better-informed decisions before disruptions occur.

## 4. Why is this topic important or interesting?

Supply chain resilience is increasingly important in a globalised and uncertain world. I find it particularly interesting how companies can balance cost efficiency with risk reduction and how the optimal sourcing strategy can differ between components. By combining risk assessments, supplier information, probability-based scenarios, and individual risk preferences, the tool could help companies make more informed decisions, improve collaboration with suppliers, and build more resilient and sustainable supply chains. From what I have heard risk managment is a very new subject in supply-chains and can change a lot.


## How is it used?

How is it used?

The tool is intended for companies that depend on external suppliers for components, materials, or products. It can be used during supplier selection, sourcing strategy planning, and regular supply chain risk assessments, as well as when external events create new risks.

The process would work as follows:

Enter supplier information: The user adds available suppliers and relevant information about their components, locations, lead times, transportation methods, and potential risks. Information about sub-suppliers can also be included when available.

Assess potential risks: The tool evaluates possible disruptions, such as strikes, natural disasters, geopolitical events, tariffs, and transportation problems. Users can adjust risk assessments based on their own knowledge and priorities.

Set preferences: The user specifies priorities such as cost, delivery reliability, sustainability, ethical working conditions, and risk tolerance.

Compare sourcing strategies: The tool compares possible approaches, such as using one supplier, multiple suppliers, or maintaining safety stock.

Receive a recommendation: Based on the available information and the user's preferences, the tool recommends a suitable sourcing strategy for each component or product.

Update information: Suppliers and sub-suppliers can update their status and report relevant changes, helping companies respond to emerging risks.

The main users would be supply chain managers, procurement teams, production planners, and risk management specialists. The solution should support both day-to-day decisions and long-term planning. It should be easy to use, transparent about its assumptions, and flexible enough to account for different company needs and risk preferences.


## Data sources and AI methods
The tool would use a combination of user-provided data, supplier information, and external information about potential supply chain disruptions.

Potential data sources include:

Company data: Supplier lists, component requirements, purchasing costs, lead times, inventory levels, and historical delivery performance.

Supplier data: Supplier locations, production capacity, delivery reliability, and information about sub-suppliers.

External data: Information about geopolitical events, strikes, natural disasters, trade restrictions, tariffs, and transportation disruptions.

Scenario-based data: Estimated probabilities and potential costs of different disruption scenarios.

The initial version could allow users to enter supplier information and risk estimates manually. External data sources and automated updates could be integrated in later versions.

The recommendation process would use risk assessment, scenario analysis, and decision-making based on the user's priorities. For example, it could compare the expected costs and risks of single sourcing, dual sourcing, and safety stock. If AI methods are introduced, they could help analyse large amounts of supplier and external-event data, identify patterns, and support risk predictions.

Recommendations would depend on the quality and completeness of the available data. Risk estimates and predictions should therefore be presented as uncertain rather than as guaranteed outcomes.

## Challenges

The tool would have several limitations and challenges:

Data quality and availability: Supplier information and sub-supplier data may be incomplete, outdated, or difficult to obtain.

Uncertainty: Global events are difficult to predict, and estimated probabilities may not reflect future conditions.

Complex supply chains: A disruption at one sub-supplier can affect several companies and components, making the full supply chain difficult to assess.

Cost versus resilience: The lowest-cost strategy is not necessarily the safest. Companies must decide how much additional cost they are willing to accept to reduce risk.

Ethical considerations: Recommendations should consider working conditions, sustainability, and other ethical priorities rather than focusing only on cost and delivery performance.

Transparency and accountability: Users should be able to understand why a strategy is recommended and which assumptions influence the result. The tool should support human decision-making, not replace it.

Confidentiality: Supplier relationships, prices, capacity, and risk information can be commercially sensitive and must be handled appropriately.

The tool cannot eliminate supply chain disruptions or guarantee that a recommended supplier will deliver on time. Its purpose is to make risks more visible, help companies compare alternatives, and support better-informed decisions.

## What next?

The project could be developed further in several stages:

Develop a working prototype: Create an interface where users can enter suppliers, components, risk factors, and company preferences.

Implement risk and cost calculations: Compare sourcing strategies using estimated disruption probabilities, financial consequences, and risk tolerance.

Visualise the supply chain: Display suppliers and sub-suppliers and show how disruptions could affect different components.

Integrate external data: Explore reliable data sources for geopolitical events, weather-related disruptions, transportation problems, and trade restrictions.

Enable supplier updates: Allow suppliers and sub-suppliers to update relevant information and communicate emerging risks.

Test with realistic cases: Compare the recommendations with existing sourcing decisions and evaluate whether the tool improves risk awareness and decision-making.

Improve the recommendation model: Explore optimisation methods or machine learning if sufficient reliable data becomes available.

Further development would benefit from skills in supply chain management, procurement, risk analysis, software development, data analysis, and optimisation. Input from manufacturing companies and suppliers would also be valuable for understanding practical requirements and validating the recommendations.
## Acknowledgments

* text was genereated from ChatGpt open AI and this idea comes from a course project that i did on Lunds University with my friens Oscar Sjödén.
