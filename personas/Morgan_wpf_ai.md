# WPF App Maintenance Dev Persona

## Bio

"Morgan" is a general-purpose .NET developer who occasionally builds native Windows desktop applications, but mostly maintains and updates existing WPF apps. He has a strong understanding of data binding and visualization.

## Goals and challenges

Morgan maintains multiple WPF apps for his Finance company. He has been asked to integrate some new AI features.

Morgan highly values the reliability and flexibility that using WPF offers the apps that he is responsible for maintaining. He is very familiar with data binding and visualization tools, but is new to AI and has no idea how to include his company's data so that AI can provide more customization for the users of his Finance apps.

Morgan is also feeling frustrated wtih the dated look and feel of his WPF apps. He isn't sure how to bring them up to par with modern looks and standards.

Morgan watched a presentation at the 2024 Microsoft Build conference that talked about Windows Copilot Runtime and Windows Copilot Library. He has concerns about the Recall feature, but is very interested in Phi Silica and it's potential to make his job of integratign AI features into his company's WPF apps easier.

Morgan nees to ensure that the WPF apps he maintains meet Finance industry compliance and security standards, but the data that he works with to make Finance predictions is public data and not under any particular data privacy restriction.

Morgan is most familiar with C# and Python. He uses Visual Studio as his IDE. Jamie works exclusively on a Windows device.

## Basic Scenarios

1. Morgan needs to learn about how to integrate new Windows AI features into his existing WPF apps.
2. Most of the legacy WPF apps at Morgan's company target the .NET Framework version of WPF. Morgan needs to learn how to update one of these legacy apps to target .NET 8 or later to improve its performance and security, as well as leverage some of the companies shared class libraries that currently target .NET 8.
3. After updating their WPF app to .NET 8, it needs to consume some Windows App SDK APIs. Morgan isn't sure if this is possible and wants to learn more about how they can do this.

## Advanced scenarios

1. Integrating AI-Powered Customization into WPF Applications

   Morgan's team is tasked with developing an AI-powered recommendation system within the WPF apps that suggests personalized finance tools and resources based on users' behaviors and previous interactions. The team must:

   - Explore the Windows Copilot Runtime and its ability to recall user preferences while ensuring privacy and security compliance.
   - Leverage Phi Silica to create dynamic AI responses that adapt to different financial scenarios (e.g., forecasting, risk management).
   - Implement machine learning models that analyze public financial data and provide real-time predictive analysis directly in the WPF app.

2. Implementing Real-Time Data Streaming and Visualization

   Morgan's team needs to introduce real-time data streaming into their WPF apps. They aim to:

   - Utilize Azure Event Hubs to integrate real-time financial data streams into the WPF apps, allowing users to see up-to-date stock prices, market trends, and forecasts.
   - Use Azure AI tools, alongside WPF's data visualization capabilities, to display these streams dynamically in graphs and charts.
   - Ensure smooth performance and user-friendly interfaces even with heavy data processing, ensuring that the app remains responsive during real-time updates.

3. Compliance-Driven AI Implementations for Finance

   Morgan’s team must ensure that AI-driven features comply with strict financial industry standards. The challenge here is:

   - Integrating AI models that comply with the company's legal and ethical guidelines while using public financial data responsibly.
   - Ensuring AI predictions and recommendations within the WPF apps follow guidelines for transparency, accountability, and explainability, as required by financial regulators.
   - Utilizing .NET 8's enhanced security features to protect against potential vulnerabilities introduced by AI and machine learning models.

4. Automating Regression Testing for .NET 8 Migration

   After migrating their WPF apps to .NET 8, Morgan’s team needs to:

   - Automate comprehensive regression testing for compatibility issues that could arise from using Windows App SDK APIs alongside legacy WPF components.
   - Set up automated CI/CD pipelines using Azure DevOps or GitHub Actions to manage updates and bug fixes efficiently across multiple apps.
   - Ensure that all performance benchmarks are met and the app’s stability is maintained after the transition to .NET 8.

5. Building AI-Assisted User Onboarding and Training

   Morgan’s team is tasked with building an intelligent onboarding and training system within the WPF apps that helps new users understand the app’s features more quickly:

   - Using Windows Copilot Library to provide step-by-step instructions and tutorials based on users’ roles and behaviors.
   - Leveraging AI to create context-sensitive help guides that evolve based on user activity, helping them learn financial tools and reporting features within the WPF app faster.
   - Developing a feedback loop within the AI system to allow users to rate the effectiveness of the onboarding experience, which then informs future updates.

## Additional Demographics

- **Years of experience:** 8
- **Industry:** Finance
- **Job title:** Software and Data Visualization Engineer
- **Preferred coding languages:** C#, Python, Visual Studio, WPF
