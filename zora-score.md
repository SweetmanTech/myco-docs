# Zora Score

Zora Score is a metric designed to measure a user's engagement and activity within the Zora ecosystem. It provides creators and collectors with a quantitative representation of their contributions and interactions on the platform.

## Score Components

The Zora Score is calculated using four main components, each contributing equally to the final score:

1. **Profile (25%)**: Evaluates the completeness of a user's profile, including linked socials, profile picture, and description.
2. **Created (25%)**: Measures the tokens and collections created by the user.
3. **Collected (25%)**: Accounts for interactions such as comments and tips.
4. **Earned (25%)**: Considers various earning activities, including createReferral, mintReferral, creator earnings, and Zora-specific earnings.

## API Usage

To retrieve a user's Zora Score, you can use the Myco API. Here's how to access the score data:

### Endpoint

GET https://api.myco.wtf/api/profile?address={user_address}

### Example Request

```bash
curl -X GET "https://api.myco.wtf/api/profile?address=0x33912a0d6beff5fb8e5b70688ce858d5e7e8104e"
```

### Response

The API returns a JSON object containing various profile details, including the Zora Score. The score information can be found in the `zoraScore` field of the response.

## Interpreting the Score

The Zora Score provides insights into a user's overall engagement and contribution to the Zora ecosystem. A higher score indicates more active participation across the four main components.

Creators and collectors can use this score to:

- Gauge their level of activity and contribution on the platform
- Set goals for increasing their engagement
- Compare their activity levels with other users
- Potentially unlock new features or opportunities based on their score (subject to platform policies)

## Note

The Zora Score calculation method may be subject to changes and improvements over time. Always refer to the latest documentation for the most up-to-date information on score calculation and interpretation.
