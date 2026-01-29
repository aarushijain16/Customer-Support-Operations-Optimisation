# Customer Support Operations Optimisation
## *Call center optimisation project for a B2B software support environment*

# Overview

This project demonstrates how data-driven operations analytics can be applied to optimise customer support performance in a high-volume technical call center environment.

Working with a simulated Remote Support Unit (RSU) at Delwarca Software, I analysed why customer wait times and dissatisfaction persisted despite the introduction of a new “Rapid ID” call routing process.

Using:

- Business process mapping

- Operational data analysis

- Queueing theory and capacity analysis

- Discrete-event simulation modelling

The goal was to identify true operational bottlenecks, balance agent and senior associate workloads, and design practical, data-backed process improvements that reduce customer wait times and improve service efficiency without increasing headcount.

# Business Problem

Delwarca Software’s Remote Support Unit was facing:

- Persistent long customer wait times

- Declining customer satisfaction

- Overloaded Senior Associates despite available capacity elsewhere

- Limited visibility into true operational bottlenecks

The newly introduced “Rapid ID” process was intended to speed up resolution by routing calls through Director Associates, but instead:

- Increased escalation to Senior Associates

- Created uneven workload distribution

- Made queue times unpredictable

Key questions addressed:

- Why did wait times remain high despite process changes?

- Where were the real capacity constraints in the system?

- How were Associates vs. Senior Associates being utilised?

- Which operational changes would actually improve customer experience?

# Solution Approach

I designed a structured, data-driven operational analysis supported by simulation modelling.

🔹 Process Analysis & Current-State Mapping

- Mapped “Pre-Rapid ID” vs. “Rapid ID” call flows

- Identified decision points, escalations, and customer pain areas

- Visualised agent handoffs and queue dependencies

🔹 Operational Data Analysis

- Analysed call arrival rates, hold times, talk times, and resolution rates

- Calculated capacity, utilisation, and throughput by role

- Identified true drivers of queue buildup and delays

🔹 Queueing & Resource Bottleneck Analysis

- Assessed workload distribution across Associates and Senior Associates

- Identified over-utilisation of Senior Associates as the critical constraint

- Highlighted risks of unconstrained requests for specific experts

🔹 Simulation Modelling (What-if Scenarios)

- Built discrete-event simulation models using Simul8

- Validated real-world issues observed in operations

- Tested alternative routing rules and staffing strategies

- Quantified impact on wait times, utilisation, and resolution efficiency

# Key Business Insights and Strategic Impact
*(Translated for customer support and operations teams)*

- Rapid ID reduced initial hold time but increased overall handling time
 → End-to-end flow optimisation matters more than first-response speed

- Senior Associates became the system bottleneck
 → Expertise concentration drove long queues and customer frustration

- Unrestricted requests for specific Senior Associates caused queue volatility
 → Poor predictability made capacity planning ineffective

- Simulation showed alternative routing strategies could significantly reduce wait times
 → Process redesign delivered higher impact than adding headcount

# Strategic Recommendations

- Introduce controlled routing to Senior Associates based on issue complexity

- Redesign escalation logic to reduce unnecessary handoffs

- Balance workload across Associates before escalation

- Use simulation modelling before rolling out operational changes

- Track utilisation and queue metrics continuously, not reactively

# Tools and Technologies

- Simul8 (Discrete-event simulation & scenario testing)

- Microsoft Excel (Operational data analysis & calculations)

- Lucidchart (As-is and to-be process mapping)

- Queueing theory and capacity modelling

# Why this Matters for Operations Teams

This project shows how analytics can:

- Diagnose hidden operational bottlenecks

- Improve customer experience without increasing costs

- Support evidence-based process redesign

- Reduce risk before implementing large-scale changes

The same approach can be applied to:

- Customer support and call centers

- Shared service operations

- Tech support and BPO environments

- Any queue-based service system

# 📌 Note

This project is based on a simulated business case using representative operational data to mirror real-world call center constraints and decision-making scenarios.

# 💬 How I Can Help You

If your team wants to:

- Reduce customer wait times

- Optimise support team utilisation

- Test operational changes before implementation

- Make data-driven service design decisions

I can apply this framework to your real operational data and deliver:

- Bottleneck and capacity analysis

- Simulation-based scenario testing

- Clear, actionable operational recommendations

- Decision-ready dashboards and insights
