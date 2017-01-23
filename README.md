# Work bot

## Features

### Start

This will set start of working time.

```
/workbot start
```

Returns following message:
- Started working time: tuesday, **6.5.2017** at **7:45**. Time to get work done, we need to make some money.

### Status

This will show remaining working time.

```
/workbot status
```

Returns following message:
- Remaining working time: **1:45**. Oh, the time flies so fast.

### End

This will set end of working time.

```
/workbot end
```

Returns following message:
- Ended working time: tuesday, **6.5.2017** at **15:45**. Well, tomorrow is another day. Good job!

---

## Automation

Command `/workbot status` could be called automatically when aproaching to end time.

## API

Run localtunnel:

```
lt --port 8765 --subdomain myworkbot
```

Url:

https://myworkbot.localtunnel.me

// Deprecated idea: Using service api.ai -> Perhaps another day.