---
title: Understanding, Information & Opportunity
nextjs:
  metadata:
    title: Understanding, Information & Opportunity
    description: How can we measure capability effectiveness? How can we ensure we're fairly assigning accountability? There are three aspects to both!
---

How can we measure capability effectiveness? How can we ensure we're fairly assigning accountability? There are the same three aspects to both!


---


## Appraising your organisation against the PSCF


One of the goals of this project is to help you answer the question, "How capable are we at security?" for your organisation. You can use the PSCF to:

* Identify missing security capabilities you need to have 
* Evaluate the security capabilities you are doing to see if improvements are needed
  
The first is straightforward: check the capabilities of the PSCF that map to regulatory frameworks or industry standards you need to comply with and see if your organisation is currently doing them.

The second requires a scale to evaluate your capability effectiveness against. In the PSCF, we provide three aspects of capability effectiveness to measure yourself against—Understanding, Information and Opportunity.

## Understanding

### Overview

Having the knowledge to carry out the tasks a security capability needs is very important. At the lowest level, your teams may need to learn that a particular security capability exists in the first place.

{% callout title="You should know!" %}
If your organisation supplies software to the US Federal Government, then the [Minimum Standards for Developer Verification of Software](https://www.nist.gov/publications/guidelines-minimum-standards-developer-verification-software) that the government requires includes threat modelling, a capability in the PSCF. Often, teams are unaware of this practice and have never done it before, so you would have a known Understanding gap that you need to close.
{% /callout %}

### The 5-point scale

The PSCF uses Bloom’s Revised Taxonomy, a well-established means for measuring understanding:

1. **Remember**: _Define, duplicate, list, memorise_
2. **Understand**: _Describe, discuss, identify, select_
3. **Apply**: _Implement, use, interpret, operate_
4. **Analyse**: _Organise, compare, examine, test_
5. **Evaluate**: _Appraise, defend, select, support_

## Information

### Overview

All of the security capablities in the PSCF have an aspect of information, or data, to them. The information can be required to:

* Let the people responsible for performing the capability know that it now needs doing
* Feedback to the people responsible that the tasks required for the capability have been carried out satisfactorily
* Alert the person accountable for ensuring the capability is carried out that the reponsible people aren't doing it

Good, high quality data is frequently lacking for security in software delivery so this is an aspect of a capabilty's effectiveness that needs closely looking at as part of an appraisal.

### The 5-point scale

There isn't a commonly-used measure of data quality or effectiveness that the PSCF project team are aware of (if you know of one please let the team know!), so we created our own for the framework and it has proven very useful in real-world applications of the framework:

1. **Incidental Data**: _Unstructured & unreliable_
2. **Owned & Managed**: _Able to be improved_
3. **Correlated**: _Clearly related & relevant_
4. **Structured & Automatable**: _Predicatable & machine-readable_
5. **Behaviour Changing**: _Compellingly presented & reliable_

## Opportunity

### Overview

The last thing that determines a capability's effectiveness is Opportunity and it has two aspects: time and tools.

#### Time

Even with a high level of knowledge about a security capability and with great data available, if a team simply has no time to carry out the tasks required then the level of that capability's effectiveness is essentially zero.

{% callout type="warning" title="Accountability Failures" %}
In the software world this is frequently caused by driving a team to deliver new features so fast that corners are cut on quality, including security. If the decision-maker for a team's work priorities is not accountable for the security quality of the software product delivered then this is almost inevitable.
{% /callout %}

This aspect of Opportunity can be improved by increasing the number of people available to carry out delivery activities or by investing in time to automate tasks so that security capabilities are implemented without requiring much, if any, of the team's time.

#### Tools

With plenty of time available to carry out the tasks a capability requires but lacking essential tools needed, you also have an Opportunity problem. Software security testing might require a tool to perform analysis of source code, threat modelling might require a playing card-based approach like [OWASP Cornucopia](https://owasp.org/www-project-cornucopia/). If teams don't have access to necessary tools then, again, capability effectiveness will be essentially zero.


### The 5-point scale

As with information, the PSCF project team aren't aware of a widely-used standard for measuring opportunity. Our self-defined scale has proven very applicable in use:

1. **Ad-hoc & Chaotic**: _Random acts of capability_
2. **Reactive**: _Activity done in response to issues_
3. **Scheduled**: _Activity on a regular cadence_
4. **Proactive**: _Activity done ahead of issues_
5. **Low-impace**: _Automated or an efficient team activity_
