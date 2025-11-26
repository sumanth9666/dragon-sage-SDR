# 🐉 Dragon Sage — Razorpay SDR Voice Agent (Day 5)

This project transforms **Dragon Sage** into a **voice-based Sales Development Representative (SDR)** for Razorpay.  
The agent speaks like a calm, wise, professional guide who:
- Answers Razorpay FAQs correctly (with no hallucinations)
- Understands what the visitor is building
- Collects lead details through friendly conversation
- Generates a clean JSON lead object at the end of the call

Dragon Sage does not “sell hard.”  
It listens, helps, and guides — just like a wise SDR mentor in a tech café.

---

## 🏢 Razorpay Company Data Used by Dragon Sage

```json
{
  "company_name": "Razorpay",
  "overview": "Razorpay is a leading Indian fintech and payment gateway platform that enables businesses to accept and process online payments via a wide range of payment methods (cards, UPI, net banking, wallets, etc.). It supports small and medium enterprises as well as large businesses, offering seamless integration, secure transactions, and a full payment suite. Razorpay also offers products like Payment Gateway, Payment Pages, Invoices, Smart Collect, and more.",
  "who_is_it_for": "Startups, freelancers, SMEs, e-commerce stores, large enterprises — basically any business that needs to accept online payments in India.",
  "pricing": "Razorpay’s standard plan charges 2% per transaction for most Indian cards, UPI, netbanking and wallets. There is no setup fee or annual maintenance fee. Pricing for other payment modes and enterprise customers may vary. GST is applicable on fees.",
  "faqs": [
    {
      "question": "What payment methods does Razorpay support?",
      "answer": "Razorpay supports credit cards, debit cards, net banking, UPI, and many popular wallets — giving customers flexibility in how they pay."
    },
    {
      "question": "Do you charge a setup fee to start using Razorpay?",
      "answer": "No — Razorpay’s standard plan has no setup fee or annual maintenance fee. You pay per transaction."
    },
    {
      "question": "Who can use Razorpay?",
      "answer": "Businesses of all sizes: freelancers, small businesses, e-commerce shops, digital startups, as well as large enterprises."
    },
    {
      "question": "Is Razorpay secure and compliant?",
      "answer": "Yes — Razorpay is PCI DSS Level 1 compliant and follows robust security and compliance standards to safeguard transactions."
    },
    {
      "question": "Can I test integration before going live?",
      "answer": "Yes — Razorpay offers a sandbox/test mode where you can integrate and test without real transactions using test API keys and test card details."
    }
  ]
}
