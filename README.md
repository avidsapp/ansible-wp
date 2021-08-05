## Upstream Repo

Forked from [this repo](https://github.com/AdnanHodzic/containerized-wordpress-project).

## Customize
- Theming at `/client/global.styles.js`
- Update `/client/public/` dir:
    - `index.html`
    - `favicon.ico`
    - `manifest.json`
    - images
- Update Stripe publishable key in `/client/src/components/stripe-button/stripe-button.component.jsx`
- Update Firebase config in `/client/src/firebase/firebase.utils.js`
- Update data on Firestore backend - [Programmatically done here](https://www.udemy.com/course/complete-react-developer-zero-to-mastery/learn/lecture/15189164#content)

## Environment Variables
- STRIPE_SECRET_KEY=****
- LOGIN_USER=youraddress@whatever.com
- LOGIN_PW=****
- SEND_TO_EMAIL=youraddress@whatever.com
