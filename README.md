# Citysnap — Child Safety Policy (README)

This folder contains the **Child Safety Standards** documents required for Google Play’s CSAE/CSAM (Child Sexual Abuse and Exploitation / Child Sexual Abuse Material) compliance and related app-store declarations.

---

## Files

| File | Purpose |
|------|---------|
| [`child-safety-policy.md`](./child-safety-policy.md) | Markdown source — easy to edit, copy into Play Console, or convert to other formats |
| [`child-safety.html`](./child-safety.html) | Hosted web page — upload to your website for a public URL |
| This README | How to publish and use the policy |

---

## What this policy is for

- **Google Play Console** → App content → **Child safety** (CSAE/CSAM standards)
- Public URL that Play can link to (recommended)
- Law enforcement / user reference for how Citysnap handles child safety

**App name:** Citysnap  
**Policy contact:** harshaldharpure9922@gmail.com  
**General support:** support@citysnap.app  
**Effective date:** March 31, 2026  

---

## Host the policy online

Play Console works best with a **public HTTPS URL**.

### Recommended URL

```
https://citysnap.app/child-safety
```

### Steps

1. Upload `child-safety.html` to your web host (same place as `privacy.html`).
2. Configure the server so `/child-safety` serves that file (or rename to `child-safety/index.html`).
3. Open the URL in a browser and confirm it loads without login.

### Optional: link from other pages

Add a footer link on your privacy and guidelines pages:

```html
<a href="https://citysnap.app/child-safety">Child Safety Standards</a>
```

---

## Google Play Console setup

1. Open [Google Play Console](https://play.google.com/console) → your app (**Citysnap**).
2. Go to **Policy** → **App content** → **Child safety** (or CSAE/CSAM section).
3. Provide:
   - **Child safety standards URL:** `https://citysnap.app/child-safety`
   - **Contact email for CSAE/CSAM:** `harshaldharpure9922@gmail.com`
4. Confirm your app has in-app reporting (Citysnap: **Report** on posts/comments, **Block** on users).
5. Save and submit for review if prompted.

---

## How this relates to your app

Citysnap is a **local city social app** (not anonymous dating). The policy reflects:

- Real-name posts and comments  
- City-based feeds (Bangalore, Pune, Hyderabad, Chennai, Mumbai, Delhi)  
- User tools: **Report** and **Block**  
- Minimum age: **13+** (aligned with [`privacy.html`](./privacy.html))  
- Account deletion from Profile  

---

## Updating the policy

1. Edit **`child-safety-policy.md`** (source of truth for text).
2. Apply the same changes to **`child-safety.html`** (keep HTML in sync).
3. Bump the **Effective date** at the top of both files.
4. Re-upload `child-safety.html` to your website.
5. No app release is required unless you add an in-app link to this URL.

---

## Related documents in `docs/`

| Document | URL (when hosted) |
|----------|-------------------|
| Privacy policy | `https://citysnap.app/privacy` → [`privacy.html`](./privacy.html) |
| Child safety | `https://citysnap.app/child-safety` → [`child-safety.html`](./child-safety.html) |
| Deep links | [`assetlinks.json`](./assetlinks.json) → `https://citysnap.app/.well-known/assetlinks.json` |
| Play launch checklist | [`PLAY_STORE_LAUNCH.md`](./PLAY_STORE_LAUNCH.md) |

---

## Quick checklist before Play submission

- [ ] `child-safety.html` live at `https://citysnap.app/child-safety`
- [ ] Contact email `harshaldharpure9922@gmail.com` entered in Play Console
- [ ] Privacy policy live at `https://citysnap.app/privacy`
- [ ] Data safety form matches actual data use (Firebase, S3, FCM, Analytics)
- [ ] In-app **Report** and **Block** tested on a real build

---

## Questions?

Child safety / legal: **harshaldharpure9922@gmail.com**  
App support: **support@citysnap.app**
