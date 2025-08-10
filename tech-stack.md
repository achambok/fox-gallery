# Technology Stack

## Frontend
- **React**: Building interactive user interfaces
- **Next.js**: Server-side rendering, routing, and static site generation
- **Tailwind CSS**: Utility-first CSS framework for rapid UI development

## Backend
- **Node.js**: JavaScript runtime for server-side logic
- **Express**: Web framework for building RESTful APIs

## Database
- **PostgreSQL**: Relational database for structured data storage
- **Supabase**: Backend-as-a-service for authentication, database, and storage

## Cloud & Storage
- **AWS S3**: Scalable object storage for user-uploaded content
- **Supabase Storage**: Alternative cloud storage solution

## AI/ML
- **Python**: Language for AI/ML model development
- **TensorFlow**: Deep learning framework
- **OpenAI**: Pre-trained models and APIs for advanced AI features

## Monitoring & Observability
- **Prometheus**: Metrics collection and monitoring
- **Grafana**: Visualization and alerting

## CI/CD
- **GitHub Actions**: Automated testing, building, and deployment

---

_This stack is modular and can be adapted as the project evolves._

# 🛠️ Tech Stack

## 🌐 Frontend (Client)
- React.js / Next.js
- Tailwind CSS
- Supabase Auth UI
- PWA Support (for offline gallery access)

## 🔐 Authentication
- **Supabase Auth** – Email, OAuth (Google, Apple, GitHub)
- JWT tokens with refresh rotation
- Rate limiting via Cloudflare

## 💳 Payments & Subscriptions
- **Stripe** – Subscription tiers, invoicing, webhooks
- User tier management (Free, Pro, Family, Enterprise)

## ⚙️ Backend & API
- **Cloudflare Workers** – Edge functions for low-latency API
- **Vercel** – Fallback deployment & SSR
- REST + partial GraphQL via D1 query layer

## 🗃️ Databases
- **Supabase PostgreSQL** – Primary DB (users, metadata, permissions)
- **Cloudflare D1** – Edge-optimized SQLite for metadata caching
- GDPR-compliant data tagging & region-aware storage

## ☁️ Storage
- **Backblaze B2** – Primary object storage (cost-efficient)
- Multi-region buckets (US, EU, APAC)
- Signed URLs via Workers for secure access

## 🌍 CDN & Security
- **Cloudflare CDN** – Global media delivery
- **WAF, DDoS Protection, GeoIP Blocking**
- Geo-restriction enforcement based on user location and policy

## 🤖 AI & Moderation
- Custom lightweight models (TensorFlow.js / ONNX)
- Content tagging (faces, objects, scenes)
- NSFW/spam detection (via moderation API or self-hosted)
- Metadata enrichment pipeline

## 📣 Social Sharing
- OAuth to Facebook, X (Twitter), Instagram, LinkedIn
- Permission validation via API layer
- Expiry-limited shared links

## 📊 Logging & Monitoring
- **Sentry** – Error tracking
- **Cloudflare Analytics** – Request monitoring
- **Logflare** (for Supabase) or **Datadog** – Centralized logs
- Alerting via Slack/PagerDuty on anomalies

## 📢 Marketing & Analytics
- **Google Analytics 4** (opt-in)
- **Meta Pixel, TikTok Pixel** (for ad campaigns)
- **Mailchimp / Resend** – Email campaigns
- UTM tracking & funnel analysis
