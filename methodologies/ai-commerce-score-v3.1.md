# AI Commerce Score™

## Methodology v3.1

The scoring model behind the AI Commerce Graph.

Eight factors measuring how AI shopping agents see, interpret, trust, and recommend ecommerce stores.

Built for the era where AI decides who gets the sale.

**Updated:** May 2026
**Author:** Daniel, Atom Foundry
**Version:** 3.1 · 8 factors · 100 points

---

## Evaluated By

* Alexa for Shopping
* Google AI Mode
* ChatGPT Shopping
* Shopify AI
* Perplexity
* Apple Intelligence

---

# Why This Scoring Model Exists

AI shopping agents are already routing commerce.

Shopify confirmed it in May 2026. AI-referred orders grew 13x year over year in Q1 2026. AI-referred orders convert at 50% higher rates and carry 14% higher average order value than organic traffic.

The shift from search-first to recommendation-first commerce is happening right now, not in the future.

The problem is that AI agents evaluate stores on completely different signals than Google does.

* Schema markup
* Machine-readable trust
* Semantic clarity
* Visual consistency
* Feed accuracy

Most stores have never optimized for any of these.

They rank well on Google and are invisible to AI.

> Your store is becoming a product database for AI agents. The question is whether that database is readable.

The old funnel:

```text
Google
↓
Website
↓
Checkout
```

The new funnel:

```text
AI Conversation
↓
AI Recommendation
↓
Instant Purchase
```

The AI Commerce Score is Atom Foundry's answer to the question every DTC founder should be asking right now:

> When a buyer asks an AI agent to recommend a product in my category, does my store show up?

And if it does:

> Does AI recommend me confidently or weakly?

---

# Score Composition

## Eight Factors · 100 Points Total

| Factor                            | Weight |
| --------------------------------- | ------ |
| Semantic Visuals & Image Clarity  | 15%    |
| AI Structured Signals             | 15%    |
| Core Technical & Interpretability | 15%    |
| AI Trust & Transaction Confidence | 15%    |
| Commerce & Feed Accuracy          | 15%    |
| User Intent Match                 | 10%    |
| Recommendation Confidence         | 10%    |
| External Authority Signals        | 5%     |

---

## Thresholds

| Score  | Meaning                  |
| ------ | ------------------------ |
| 85–100 | Highly Recommendable     |
| 70–84  | Moderately Recommendable |
| 50–69  | Low Confidence           |
| 0–49   | AI Invisible Risk        |

**Current Benchmark**

* 6,789 stores scanned
* Average score: 45
* 52% score below 50
* 0 stores above 85

---

# Factor Definitions

## 01. Semantic Visuals & Image Clarity

**Weight: 15%**

AI vision systems now read product images, not just text.

### Sub-Metrics

#### Alt Text Matching (8%)

We send product images to GPT-4o Vision and compare semantic descriptions against actual alt text.

**Tool**

* GPT-4o Vision API
* HTML Parser

#### Image Context & Overlays (4%)

Checks whether critical information exists as image overlays rather than crawlable HTML.

**Tool**

* Vision API Overlay Detection

#### Product Visual Consistency (3%)

Verifies that image content matches product descriptions.

**Tool**

* Vision API
* Structured Data Comparison

---

## 02. AI Structured Signals

**Weight: 15%**

Structured data is the primary language of AI shopping systems.

### Sub-Metrics

#### Schema.org Validation

Validates:

* Product
* Offer
* AggregateRating

**Tool**

* JSON-LD Parser
* Schema Validator

#### Merchant Identity

Checks Organization and Store schema.

**Tool**

* Knowledge Graph Verification

#### AI Root Indexing

Checks llms.txt presence and quality.

**Tool**

* llms.txt Analyzer

---

## 03. Core Technical & Interpretability

**Weight: 15%**

A technically broken store is an invisible store.

### Sub-Metrics

#### Crawler Accessibility

Checks:

* robots.txt
* GPTBot
* ClaudeBot
* AppleBot

#### Core Web Vitals

Measures:

* LCP
* CLS

**Tool**

* Google PageSpeed API

#### DOM Structure Quality

Evaluates:

* H1–H3 hierarchy
* Semantic HTML
* DOM cleanliness

---

## 04. AI Trust & Transaction Confidence

**Weight: 15%**

AI agents perform machine-readable trust checks before recommendations.

### Sub-Metrics

#### Machine-Readable Policies

Checks:

* Returns Policy
* Terms of Service

#### Checkout Gateway Accessibility

Tests:

* Cart accessibility
* Checkout flow
* Agent compatibility

#### Legal Identity Transparency

Checks:

* Business name
* Address
* Contact information

---

## 05. Commerce & Feed Accuracy

**Weight: 15%**

AI agents increasingly complete purchases directly.

### Sub-Metrics

#### Real-Time Price Sync

Compares:

* Website pricing
* Product feeds
* Shopping feeds

#### Inventory Integrity

Verifies consistency across:

* Feed
* Schema
* Live product page

---

## 06. User Intent Match

**Weight: 10%**

AI matches stores to intent, not keywords.

### Sub-Metrics

#### Long-Tail Semantic Coverage

Measures alignment with real-world AI shopping prompts.

**Tool**

* Semantic Embeddings
* LLM Similarity Analysis

---

## 07. Recommendation Confidence

**Weight: 10%**

Appearing is not the same as being recommended.

### Sub-Metrics

#### Reviews Schema & Sentiment

Measures:

* AggregateRating
* ReviewCount
* Sentiment

**Tool**

* Schema Validation
* Sentiment Analysis

---

## 08. External Authority Signals

**Weight: 5%**

AI systems learn from the broader web.

### Sub-Metrics

#### Knowledge Graph Footprint

Measures visibility across:

* Reddit
* Perplexity
* LLM Citations
* AI Indexes

**Tool**

* Citation Tracking
* Knowledge Graph Analysis

---

# Score Interpretation

## 85–100

### Highly Recommendable

AI agents understand, trust, and confidently recommend your store.

## 70–84

### Moderately Recommendable

AI recommends your store but stronger signals would increase frequency and ranking.

## 50–69

### Low Confidence

AI sees your store but recommendation confidence remains weak.

## 0–49

### AI Invisible Risk

Critical gaps prevent AI systems from recommending your business.

---

# About Atom Foundry

Atom Foundry is building the AI Commerce Graph™.

Our mission is to measure how AI systems:

* Discover
* Understand
* Trust
* Recommend

commerce brands in the age of AI-native shopping.
