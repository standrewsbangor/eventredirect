# 🔁 St Andrew's Bangor — Event Redirects

This repository powers the [standrewsbangor.church](https://standrewsbangor.church) redirect service, hosted via Netlify.

It provides user-friendly URLs like:

- `/events/bereavement-journey`
- `/events/community-fun-day`

...which redirect to the relevant ChurchSuite event pages.

The root domain (`/`) also redirects to the main website:  
👉 [http://standrewsbangor.org.uk](http://standrewsbangor.org.uk)

---

## 📂 How it Works

Netlify uses the `_redirects` file in this repository to define all redirects.

Each line in the `_redirects` file looks like this:

```txt
/source-path   https://destination-url   301
