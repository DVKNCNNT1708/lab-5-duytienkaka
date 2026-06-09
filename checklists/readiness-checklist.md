# Readiness Checklist - Lab 05

Day la danh sach kiem tra de dam bao stack Docker Compose da san sang truoc khi gui bai.

- [x] **Database ready:** container DB da chay va phan hoi `pg_isready`.
- [x] **AI service ready:** container AI service tra ve `200` cho `/health` va `/predict`.
- [x] **API ready:** container API tra `200` cho `/health` va tao/lay readings voi bearer token hop le.
- [x] **Environment variables:** `.env.example` du thong tin runtime va khong chua secret that.
- [x] **Network & Ports:** mang `team-internal` hoat dong, API map port `8000`, AI map port `9000`, DB su dung port `5432` trong stack.
- [x] **Image tags:** image duoc build voi version hien hanh va san sang de tag/push theo quy uoc `v0.1.0-<team>`.

Ghi chu:

```text
- Compose stack da duoc cap nhat de GitHub Actions co the build, wait healthcheck va chay Newman report tu dong.
```
