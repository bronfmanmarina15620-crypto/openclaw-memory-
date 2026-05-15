# Server Security Checklist

מקור: בקשת Marina מ-2026-05-15

## המשימות המקוריות

1. ✅ Install Tailscale and give me the auth link
2. ✅ Once connected, configure OpenClaw to bind to loopback with Tailscale Serve mode (so the gateway is only reachable through Tailscale)
3. ✅ Set up UFW: default deny all incoming, allow SSH only on the Tailscale interface
4. ✅ Install and enable Fail2ban
5. ✅ Set up the allowlist so only my number can message you
6. ✅ Run "openclaw security audit --deep" and show me the results

## הערות
- כל הצ'קליסט הושלם ב-2026-05-15
- Security audit: 0 critical, 3 warn (לא דחוף)
- SSH נגיש רק דרך Tailscale (`100.120.33.24`)
- Gateway נגיש רק דרך `https://srv1567136.tail583b5f.ts.net/`

