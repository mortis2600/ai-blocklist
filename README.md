# AI & Image Generation Blocklist

A DNS blocklist for Pi-hole and AdGuard Home that blocks AI chatbots and
image generation sites. Useful for parental controls or anyone who wants
to restrict access to AI tools on their network.

## What it blocks

### AI Chatbots
- ChatGPT / OpenAI
- Claude (Anthropic)
- Google Gemini
- Microsoft Copilot
- Perplexity AI
- Character.AI
- Grok (xAI)
- DeepSeek
- Meta AI
- Kimi / Moonshot
- Hailuo AI
- Mistral AI
- Cohere
- Poe
- You.com

### Image Generation
- Midjourney
- NightCafe
- DreamStudio / Stable Diffusion
- Playground AI
- Leonardo AI
- Ideogram
- Adobe Firefly
- Tensor.art
- Civitai
- Imagine.art

## How to add to Pi-hole

1. Go to **Pi-hole Admin → Lists → Paste list URL below → Click Add Blocklist 
2. Paste the URL below
3. Assign to your desired group
4. Run `pihole -g` to update gravity

5. https://raw.githubusercontent.com/mortis2600/ai-blocklist/refs/heads/main/blocklist.txt
