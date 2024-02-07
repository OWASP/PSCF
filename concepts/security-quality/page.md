---
title: Security is an aspect of software product quality
nextjs:
  metadata:
    title: Security is an aspect of software product quality
    description: Software product quality is well defined, and security is just one aspect of it.
---

What is quality? In the world of software products this isn't a metaphysical conundrum, it's well-defined!

---

## What is software product quality

This framework uses a rigorous definition of quality for software products, the ISO25010 Software Product Quality Model.

### ISO25010 Software Product Quality Model

![A diagram showing the ISO25010 Software Product Quality Model with quality characteristics of Functional Suitability, Performance Efficiency, Compatibility, Usability, Reliability, Security, Maintainability, Flexibility and Safey](/images/iso25010-software-product-quality-model.png)

For reasons not known to the PSCF project team, this model is almost unheard of in the software delivery world. The lack of awareness is very unfortunate because the ISO quality model is comprehensive and extremely helpful in defining the things that matter for a software product.

{% callout title="Product Owners" %}
You should be particularly interested in this quality model if you're in product management. Being a product owner means you prioritise all of these aspects of quality for your customers and organisation, balancing team effort to create a product of sufficient quality. Product Owner sounds nicer than Quality Manager, though.
{% /callout %}

## Prioritising quality

The ISO team have connected the model to how a software product delivers value to a business. This means there's a left-to-right order of "importance" to it, with the highest value aspects of quality on the left and the lowest on the right. It's a generic, all industries view but look at the order and see if you agree.

Functional quality will almost always overrule any other aspect of quality. No one cares how fast, reliable or flexible your software is if it doesn't work!

Performance is the biggest contributor to your customer's perception of quality in your software product. A snappy, responsive system always feels higher quality than a slow, unresponsive one.

You might be surprised to see reliability being of lower importance. However, a system that's 99.999% available but so slow it's unusable is pretty low value.

Overall, the most visible aspects of quality to your customers are of higher value and the less visible aspects are of lower value.

{% callout type="warning" title="So can we just ignore the things on the right?" %}
Not if you want to sustainably deliver value over time!

Low security quality is an incident waiting to happen; the longer you have low security quality the more likely the incident will happen. The remaining qualities on the right chiefly impact the delivery team itself. A software product with low maintainability and flexibility will quickly lead to one with reliability, performance and functional problems for your customers.
{% /callout %}

## How to use the model

The model has a sensible order of quality importance, but it could be wrong for your organisation and product. Most software delivery teams don't have to worry much about their software's safety, but you might have to. For some products, reliability could be all-important, or performance might not be a big concern for your customers and organisation.

To start with, review the order of the model and adjust it where necessary for your purposes. Once you have a correctly prioritised quality model you have a high-level view of what's most important to your customers and to your organisation.

Next, set some quantifiable targets for each aspect of quality. From metrics that clearly indicate that you're reaching the levels of quality your customers and organisation require. We like the Service Level Objective (SLO) and Service Level Indicator (SLI) approach. Having clear measures of quality that you track over time stops it from being a subjective guessing game for the delivery team and makes for a far more effective approach to delivering high-quality software products consistently.

{% callout title="Quality Metrics" %}
In the PSCF we call these measures **Quality Metrics**. For each capability, we provide suggested SLIs that will be useful for you to track and use for your security SLOs. **Quality Metrics** are balanced against **Delivery Metrics**, measures of delivery effectiveness, to ensure you're not impacting the timely delivery of software products to your customers with excessively high requirements for quality.
{% /callout %}

Finally, track these SLIs over time and use their trends to inform your decision-making. Having early sight that performance, reliability or security quality is declining means you can re-prioritise your efforts in those areas before an incident occurs.
