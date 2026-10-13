## Summary :clipboard:
<!-- Handmatig geschreven -->


## Ticket number :link:
<!-- Jira -->

## Changes :construction:
- [ ] Frontend
- [ ] ETL
- [ ] Docs
- [ ] Infra / deploy (tofu, CI/CD, Docker)
- [ ] Config / secrets

---

## How to test :test_tube:
<!-- Lokaal testen -->

```bash
just checkout <branch>
just run <app>
```
```bash
just docker-build
```

---

## Checklist :memo:
- [ ] Zelf lokaal getest
- [ ] Tests :white_check_mark:
- [ ] Pre-commit :white_check_mark: (Linter / checks / `tofu plan`)
- [ ] README / AGENTS / docs geupdatet 
- [ ] Roborev (Opus) review
- [ ] Code gelezen
- [ ] PR is zo klein mogelijk voor functionaliteit (niet twee functionaliteiten in 1 pr)
- [ ] Jira ticket aan PR gekoppeld 

### Indien van toepassing
- [ ] Versie upgrade 
- [ ] Secrets toegevoegd / IAM rollen aangepast.
- [ ] Confluence geüpdatet (business context, roadmap, non-technische documentation).

---

## Bewuste afwijkingen van Roborev (High/Med) :warning:
<!-- Beschrijf welke High/Medium-bevindingen bewust niet zijn opgevolgd en waarom -->
