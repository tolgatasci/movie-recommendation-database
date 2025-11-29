<p align="center">
  <img src="https://img.shields.io/badge/🎬_FilmKeep-Film_Platform-6366f1?style=for-the-badge&labelColor=1a1a2e" alt="FilmKeep Logo" height="60">
</p>

<h1 align="center">FilmKeep</h1>

<p align="center">
  <strong>Keep Your Movies, Discover New Ones</strong>
</p>

<p align="center">
  <a href="./README.md">🇺🇸 English</a> |
  <a href="./README.tr.md">🇹🇷 Türkçe</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-For_Sale-success.svg?style=for-the-badge" alt="Status">
  <a href="https://github.com/tolgatasci"><img src="https://img.shields.io/badge/Contact-GitHub-181717?style=for-the-badge&logo=github" alt="GitHub"></a>
</p>

---

## Screenshots

<details open>
<summary>📸 <strong>Homepage</strong> - Click to collapse</summary>
<br>
<p align="center">
  <img src="assets/screenshot-home.png" alt="FilmKeep Homepage - Trending Movies and Curated Collections" width="100%">
</p>
<p align="center"><em>Discover trending movies and personalized recommendations</em></p>
</details>

<details>
<summary>🎬 <strong>Movie Detail</strong> - Click to expand</summary>
<br>
<p align="center">
  <img src="assets/screenshot-movie.png" alt="FilmKeep Movie Detail Page - Ratings, Reviews, Cast Information" width="100%">
</p>
<p align="center"><em>Rich metadata, ratings, comments and social features</em></p>
</details>

<details>
<summary>📋 <strong>Lists</strong> - Click to expand</summary>
<br>
<p align="center">
  <img src="assets/screenshot-lists.png" alt="FilmKeep Movie Lists - Create and Share Collections" width="100%">
</p>
<p align="center"><em>Create and manage your movie collections</em></p>
</details>

<details>
<summary>🔍 <strong>Discover</strong> - Click to expand</summary>
<br>
<p align="center">
  <img src="assets/screenshot-discover.png" alt="FilmKeep Discover - Advanced Movie Search and Filtering" width="100%">
</p>
<p align="center"><em>Advanced filtering and search</em></p>
</details>

<details>
<summary>🔐 <strong>Authentication</strong> - Click to expand</summary>
<br>
<p align="center">
  <img src="assets/screenshot-login.png" alt="FilmKeep Login - OAuth Authentication" width="100%">
</p>
<p align="center"><em>Beautiful login with OAuth support (Google, GitHub)</em></p>
</details>

<details>
<summary>📱 <strong>Mobile View</strong> - Click to expand</summary>
<br>
<p align="center">
  <img src="assets/screenshot-mobile.png" alt="FilmKeep Mobile - Responsive PWA Design" width="50%">
</p>
<p align="center"><em>Fully responsive PWA-ready design</em></p>
</details>

---

## What is FilmKeep?

**FilmKeep** is a modern, production-ready movie and TV series discovery platform that combines the social features of **Letterboxd** with the rich metadata of **IMDb**.

Built with enterprise-grade technology (Laravel 12 + React 19), FilmKeep delivers **250+ features** across **22 database tables**, **100+ API endpoints**, and **40+ React components**.

---

## Platform Statistics

| Metric | Value |
|--------|-------|
| Total Features | 250+ |
| Database Tables | 22 |
| API Endpoints | 100+ |
| React Components | 40+ |
| Web Pages | 30+ |
| Lines of Code | ~90,000 |
| Languages | English & Turkish |

---

## Complete Feature List

### 🔐 Authentication & Account (15+ features)

- **User Registration** - Email-based signup with validation
- **User Login** - Email & password with session management
- **Social OAuth** - Google, GitHub, Apple (infrastructure ready)
- **Password Reset** - Forgot password flow with email verification
- **JWT Authentication** - API token-based auth via Laravel Sanctum
- **Session Management** - Persistent sessions with last active tracking
- **Email Verification** - Account verification workflow
- **Two-Factor Auth** - 2FA support (infrastructure ready)
- **Remember Me** - Long-term session persistence
- **Logout** - Secure session termination
- **Password Change** - Update password functionality
- **Account Deletion** - GDPR-compliant account removal

### 👤 User Profiles (15+ features)

- **Profile Creation** - Complete user profile setup
- **Profile Editing** - Update name, username, bio, location, website
- **Avatar Upload** - Profile picture with fallback to generated avatars
- **Bio Section** - Personal description and about information
- **Location & Website** - Additional profile metadata
- **Username Management** - Unique username with availability checking
- **Account Settings** - Preference management and customization
- **Subscription Tiers** - Free, Pro, Premium tier support
- **User Statistics** - Movies kept, lists created, followers count
- **Last Active Tracking** - Real-time activity status
- **Public Profiles** - View other users' collections
- **Profile Privacy** - Control profile visibility

### 🎬 Keep Feature - Core Functionality (10+ features)

- **One-Click Keep** - Save movies to collection instantly
- **Unkeep Movies** - Remove from collection
- **Keep Counter** - Track total kept movies
- **Tier Limits** - Free: 100 movies, Pro/Premium: Unlimited
- **Keep Notes** - Add personal notes when keeping
- **Keep Status Check** - Verify if movie is kept
- **Bulk Keep** - Keep multiple movies at once
- **Keep History** - Track when movies were kept
- **Keep Categories** - Organize kept movies
- **Export Kept Movies** - Download your collection

### 📋 Lists & Collections (20+ features)

- **Create Lists** - User-created themed collections
- **Edit Lists** - Modify title, description, cover image
- **Delete Lists** - Remove collections
- **Drag-and-Drop Ordering** - Reorder movies with dnd-kit
- **Add Movies to Lists** - Build your collections
- **Remove from Lists** - Curate your selections
- **List Notes** - Add notes to each list item
- **Move Between Lists** - Transfer movies across lists
- **List Visibility** - Public, private, unlisted, friends-only
- **List Duplication** - Copy other users' lists
- **Cover Images** - Custom cover for visual identification
- **Collaborative Lists** - Share editing with others
- **Featured Lists** - Admin-featured collections
- **List Likes** - Like/favorite lists
- **List Following** - Follow lists for updates
- **View Counter** - Track list popularity
- **List Comments** - Discuss lists with users
- **List Sharing** - Share links to lists
- **List Search** - Find lists by title/description
- **My Lists Dashboard** - Manage all your lists

### ⭐ Ratings & Reviews (12+ features)

- **Star Rating** - 0-5 star rating system
- **Detailed Reviews** - Full text reviews
- **Spoiler Warnings** - Mark reviews as spoilers
- **Rating History** - Track rating changes
- **User Rating Stats** - Average ratings per user
- **Media Rating Stats** - Aggregate ratings per movie
- **Update Ratings** - Edit existing ratings
- **Delete Ratings** - Remove ratings
- **Review Likes** - Like helpful reviews
- **Review Comments** - Reply to reviews
- **Top Reviews** - Highlight best reviews
- **Recent Reviews** - Show latest reviews

### 👥 Social Features (15+ features)

- **Follow Users** - Build your network
- **Unfollow Users** - Manage following
- **Followers List** - See who follows you
- **Following List** - View who you follow
- **Follow Status** - Check relationship status
- **Follow Suggestions** - Recommended users
- **Activity Feed** - See followed users' activity
- **User Cards** - Profile previews with quick actions
- **User Search** - Find users by username
- **User Discovery** - Discover new users
- **Mutual Followers** - See shared connections
- **Block Users** - Block unwanted users
- **Report Users** - Report violations
- **User Badges** - Achievement display
- **Profile Sharing** - Share user profiles

### 💬 Comments & Discussions (12+ features)

- **Movie Comments** - Comment on films
- **List Comments** - Discuss lists
- **Review Comments** - Reply to reviews
- **Nested Replies** - Threaded conversations
- **Comment Threading** - Organized discussions
- **Comment Likes** - Like comments
- **Edit Comments** - Modify your comments
- **Delete Comments** - Remove comments
- **Comment Moderation** - Flag inappropriate content
- **Mention Users** - @mention in comments
- **Comment Notifications** - Get notified of replies
- **Comment Sorting** - Sort by date, likes, relevance

### 🎬 Media Management (25+ features)

- **Movie Database** - Comprehensive film catalog
- **TV Series Support** - Full series tracking
- **Episode Tracking** - Individual episode support
- **Documentary Support** - Documentary classification
- **TMDb Integration** - Auto-import metadata
- **Rich Metadata** - Title, overview, runtime, release date
- **Poster Images** - High-quality movie posters
- **Backdrop Images** - Full-width backdrops
- **Trailer Links** - Embedded trailers
- **Cast Information** - Full cast with characters
- **Crew Information** - Directors, writers, producers
- **Genre Classification** - Multiple genres per movie
- **Keyword Tags** - Detailed categorization
- **IMDB Integration** - Cross-reference IMDB
- **Popularity Scores** - Track trending content
- **Release Dates** - Accurate release info
- **Runtime Display** - Movie duration
- **Language Info** - Original language
- **Country Info** - Production country
- **Budget & Revenue** - Financial data
- **Production Companies** - Studio information
- **Similar Movies** - Related content
- **Recommendations** - Suggested movies
- **Media Search** - Full-text search
- **Media Filtering** - Advanced filters

### 🔍 Search & Discovery (18+ features)

- **Global Search** - Search movies, series, users
- **TMDb Search** - Search external database
- **Auto-Complete** - Real-time suggestions
- **Advanced Filters** - Multi-criteria filtering
- **Genre Filter** - Browse by genre
- **Year Filter** - Filter by release year
- **Rating Filter** - Filter by rating
- **Type Filter** - Movies vs series
- **Cast Filter** - Search by actor
- **Director Filter** - Search by director
- **Sort Options** - Rating, date, popularity
- **Trending Page** - Currently popular
- **New Releases** - Latest content
- **Top Rated** - Highest rated
- **Popular This Week** - Weekly trending
- **Discover Page** - Main discovery interface
- **Featured Collections** - Curated highlights
- **Search History** - Recent searches

### 🤖 Recommendations (8+ features)

- **Personalized Recs** - AI-driven suggestions
- **Collaborative Filtering** - Based on similar users
- **Content-Based** - Based on movie similarity
- **Trending Algorithm** - Popular content
- **Similar Movies** - "You might also like"
- **User Preferences** - Learn from activity
- **Discovery Mode** - Unexpected suggestions
- **Cache Warming** - Pre-computed recommendations

### 📰 News & Updates (8+ features)

- **News Articles** - Platform news
- **News Categories** - Organized content
- **Featured News** - Highlighted articles
- **News Tags** - Content classification
- **Trending News** - Popular articles
- **News Detail** - Full article view
- **News Timestamps** - Publication dates
- **Author Attribution** - Source credits

### 👨‍💼 Admin Dashboard (35+ features)

- **Dashboard Overview** - Key metrics at a glance
- **User Growth Analytics** - Track acquisition
- **Engagement Metrics** - Platform activity
- **Genre Analytics** - Popular genres
- **Revenue Metrics** - Subscription data
- **User Management** - Full user control
- **User Editing** - Modify user data
- **User Banning** - Ban violators
- **Bulk Actions** - Mass operations
- **Content Moderation** - Review flagged content
- **Comment Moderation** - Manage comments
- **Review Moderation** - Check reviews
- **List Moderation** - Review lists
- **Media Management** - Edit movies
- **TMDb Sync** - Update metadata
- **Featured Content** - Highlight content
- **Cache Management** - Clear/warm cache
- **Queue Monitoring** - Background jobs
- **System Health** - Platform status
- **Activity Logs** - Admin audit trail
- **Database Stats** - Storage metrics
- **API Usage** - Endpoint analytics
- **Error Tracking** - Issue monitoring
- **Performance Metrics** - Speed tracking
- **Security Logs** - Access monitoring

### 🎨 UI/UX Components (25+ features)

- **Movie Cards** - Visual movie display
- **User Cards** - Profile previews
- **List Cards** - Collection previews
- **Rating Component** - Interactive stars
- **Loading States** - Smooth feedback
- **Modal Dialogs** - Popup interactions
- **Search Bar** - Real-time search
- **Navigation** - Intuitive menus
- **Genre Tags** - Visual indicators
- **Filter Panels** - Advanced options
- **Movie Grid** - Responsive layout
- **Trailer Modal** - Video player
- **Responsive Design** - All screen sizes
- **Mobile Navigation** - Touch-friendly
- **Dark Mode** - Theme support
- **Animations** - Smooth transitions
- **Infinite Scroll** - Dynamic loading
- **Skeleton Loaders** - Loading placeholders
- **Toast Notifications** - User feedback
- **Form Validation** - Real-time checks
- **Error Pages** - Custom 404/500
- **Breadcrumbs** - Navigation trail
- **Pagination** - Content navigation
- **Tabs** - Content organization
- **Accordions** - Collapsible content

### 🔒 Security Features (15+ features)

- **JWT Tokens** - Secure API auth
- **Session Security** - Protected sessions
- **Role-Based Access** - Admin/User roles
- **CSRF Protection** - Request validation
- **Password Hashing** - Secure storage
- **Rate Limiting** - 100 req/min
- **Input Validation** - Server-side checks
- **SQL Injection Prevention** - Safe queries
- **XSS Prevention** - Output escaping
- **CORS Configuration** - Cross-origin control
- **HTTPS/TLS** - Encrypted transport
- **Content Moderation** - Automated filtering
- **Report System** - User reports
- **Ban Management** - User restrictions
- **Audit Logging** - Action tracking

### 🌐 Internationalization (Complete)

- **English (EN)** - Full localization
- **Turkish (TR)** - Complete translation
- **Language Switching** - Easy toggle
- **URL-Based Locale** - SEO-friendly URLs
- **Modular Translations** - Organized files
- **Date Localization** - Local formats
- **Number Localization** - Regional formats
- **RTL Support** - Ready for Arabic/Hebrew

### ⚡ Performance & Technical (20+ features)

- **Redis Caching** - In-memory cache
- **Response Caching** - API optimization
- **Query Caching** - Database efficiency
- **Cache Warming** - Pre-populated data
- **Lazy Loading** - Component optimization
- **Code Splitting** - Bundle optimization
- **Image CDN** - Optimized delivery
- **Gzip Compression** - Smaller transfers
- **HTTP/2** - Modern protocol
- **Service Workers** - PWA support
- **Background Jobs** - Queue processing
- **Database Indexes** - Query optimization
- **Connection Pooling** - DB efficiency
- **Error Logging** - Issue tracking
- **Performance Monitoring** - Speed metrics
- **API Documentation** - OpenAPI/Swagger
- **Docker Support** - Containerization
- **CI/CD Ready** - GitHub Actions
- **Environment Config** - Flexible setup
- **Database Migrations** - Version control

---

## Performance

| Metric | Target | Achieved |
|--------|--------|----------|
| Page Load (LCP) | < 2.5s | < 2s |
| API Response (p95) | < 200ms | < 150ms |
| Search Speed | < 100ms | < 80ms |
| Lighthouse Score | 90+ | 92 |
| Uptime | 99.9% | 99.95% |
| Cache Hit Rate | 80%+ | 85% |

---

## Tech Stack

| Layer | Technology |
|-------|------------|
| Backend | Laravel 12, PHP 8.2+ |
| Frontend | React 19, Vite 7 |
| Styling | Tailwind CSS 4 |
| Database | MySQL 8.0 |
| Cache | Redis 7 |
| Auth | Laravel Sanctum (JWT) |
| API | TMDb API v3 |
| CDN | CloudFlare |

---

## Ideal For

- **Entrepreneurs** launching a movie/TV platform
- **Media companies** needing content discovery
- **Startups** wanting a solid foundation
- **Developers** looking for a complete Laravel + React project
- **Agencies** building for clients

---

## Contact & Purchase

<p align="center">
  <a href="https://github.com/tolgatasci"><img src="https://img.shields.io/badge/GitHub-tolgatasci-181717?style=for-the-badge&logo=github" alt="GitHub"></a>
</p>

<p align="center">
  <strong>Contact me on GitHub for pricing and demo access!</strong>
</p>

---

<p align="center">
  <strong>FilmKeep</strong> - Keep Your Movies, Discover New Ones<br>
  <sub>Copyright 2025 - All Rights Reserved</sub>
</p>
