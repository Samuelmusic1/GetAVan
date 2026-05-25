**🚐 GetAVan**
GetAVan is a full-stack van rental web application designed to simplify vehicle booking for road trips. Built as a core capstone project during my React development journey, this application combines a dynamic user interface with a cloud database to deliver a responsive, single-page experience.

**Technologies Used:**
React
React Router
Firebase Firestore
JavaScript
CSS

**What I Learned**
Developing GetAVan served as a practical proving ground for mastering production-ready frontend paradigms:
  Declarative Routing & State Syncing
Designed custom, type-safe state bindings that link UI components directly to URL query strings (useSearchParams), treating the browser URL as the single source of truth.
Leveraged history stack states (location.state) to pass hidden tracking data between pages, creating seamless "Back to Search Results" UI return flows.
  Application Guarding & Error Resilience
Built robust wrapper components for protected route redirection, caching intended destinations to return users to their original target page post-login.
Architected strict multi-layer fallback configurations, utilizing catch-all routes (path="*") for clean 404 views and implementing defensive error-boundary patterns to handle broken API calls.
  Asynchronous Data Synchronization
Managed data orchestration between the UI layer and remote Firebase Firestore databases.
Utilized promise chaining cleanup patterns (.finally()) to cleanly govern user interface elements like global request loading indicators and form button disable toggles.

**Purpose**
The core objective of this application was to transition from writing isolated frontend layouts to engineering interconnected, data-driven single-page systems. This project demonstrates hands-on competency in routing security, state serialization, asynchronous lifecycle management, and cloud database integration.
