---
title: Security requirements not security opinions
nextjs:
  metadata:
    title: Security requirements not security opinions
    description: The PSCF team don't just want to throw their opinions on what matters in with everyone else's. This section describes the rigorous process by which the PSCF security capabilities were derived.
---

Software product delivery is complex. Cause and effect are unclear, and little empirical evidence shows that doing _activity X_ will lead to _security improvement Y_.


So, what do we do?

---

## How we derived the PSCF security capabilities

The PSCF team doesn't want to just provide their own opinion of what matters. A large body of work and rigour already exists in regulatory frameworks and industry and community standards. We analyse these frameworks and standards to derive the fundamental security capabilities they require.

Each framework or standard refers to these capabilities in its own way and places greater or lesser emphasis on certain ones, but there is a significant overlap across them.

{% callout title="Industry-specific Regulators" %}
As we analyse each framework or standard, we capture its emphasis by quantifying how effective (or "mature") it requires you to be at that security capability. So, when you appraise your organisation against the PSCF, you can see how well-prepared you are to adopt a compliance framework or industry standard!
{% /callout %}

The PSCF is a type of [Meta-analysis](https://en.wikipedia.org/wiki/Meta-analysis) across multiple bodies of work to determine the collective requirements that define Best Practice.

![A process diagram of how the PSCF derives security capabilites from regulatory frameworks and industry standards](/images/pscf-meta-analysis.png)

## What is "Best Practice"?

If it comes to a customer data breach or similar security-related incident, your organisation will be investigated for negligence by an information rights regulator or equivalent in your country.

{% callout type="warning" title="Industry-specific Regulators" %}
If your organisation operates in certain industry sectors, such as Financial Services, another regulator is likely to investigate you. If you operate across multiple countries, then many will!
{% /callout %}

These investigations typically focus on whether, as an organisation, you were doing enough to ensure adequate security in your software. The incident has shown you had a weakness somewhere in what you were doing. Was it just an unfortunate occurrence that happened despite all best efforts being made, or was it inevitable because you weren't doing what you should have been doing?

The decision usually comes down to whether you were following industry best practices for security. These best practices aren't your opinion or the opinion of your engineering or security teams. **Best practice is the collective requirements across current, published industry and community security standards**.

## The security activities that matter

So, if we don't know exactly what activities lead to the best security outcomes, then we're left with two sources of guidance for the things that we need to be doing in software product delivery:

1. Any specific requirements that our regulators have placed upon our organisation
2. Collective industry best practice

In this framework, we consider these as:

1. **External compliance obligations**. Mandatory activities you have to do as an organisation to be permitted to operate.
2. **Internal compliance obligations**. Additional activities you have committed to do as an organisation, hopefully based on an industry or community standard, to ensure you're meeting industry best security practices.

When [adopting this framework](/pscf/intro/adopting-this-framework), one of your first steps is determining what these external and internal compliance obligations are.
