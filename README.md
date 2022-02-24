## javascript

```
❯ npx autocannon -c 5 -d 5 https://javascript.sugiura.workers.dev/
Running 5s test @ https://javascript.sugiura.workers.dev/
5 connections

┌─────────┬──────┬───────┬───────┬───────┬──────────┬──────────┬────────┐
│ Stat    │ 2.5% │ 50%   │ 97.5% │ 99%   │ Avg      │ Stdev    │ Max    │
├─────────┼──────┼───────┼───────┼───────┼──────────┼──────────┼────────┤
│ Latency │ 9 ms │ 11 ms │ 19 ms │ 23 ms │ 13.39 ms │ 31.38 ms │ 694 ms │
└─────────┴──────┴───────┴───────┴───────┴──────────┴──────────┴────────┘
┌───────────┬────────┬────────┬────────┬────────┬────────┬───────┬────────┐
│ Stat      │ 1%     │ 2.5%   │ 50%    │ 97.5%  │ Avg    │ Stdev │ Min    │
├───────────┼────────┼────────┼────────┼────────┼────────┼───────┼────────┤
│ Req/Sec   │ 167    │ 167    │ 403    │ 418    │ 359.4  │ 96.68 │ 167    │
├───────────┼────────┼────────┼────────┼────────┼────────┼───────┼────────┤
│ Bytes/Sec │ 123 kB │ 123 kB │ 296 kB │ 307 kB │ 264 kB │ 71 kB │ 123 kB │
└───────────┴────────┴────────┴────────┴────────┴────────┴───────┴────────┘

Req/Bytes counts sampled once per second.
# of samples: 5

2k requests in 5.12s, 1.32 MB read
```