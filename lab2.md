---
config:
  theme: redux
  layout: fixed
---
flowchart TD
    n6[" "] --> n5["Load Balancer"]
    n7[" "] --> n3["VM1: React front"]
    n8[" "] <--> n2["VM3: Postgre database"]
    n9[" "] <--> n1["VM2: Flask Back"]
    A(["Client(INTERNET)"]) --> C["Firewall"]
    n10["API call"]
    n11["Queries"]
    n12["https"]
    n13["Virtual Private Network"]
    n6@{ shape: anchor}
    n5@{ shape: rect}
    n7@{ shape: anchor}
    n8@{ shape: anchor}
    n2@{ shape: cyl}
    n9@{ shape: anchor}
    n10@{ shape: text}
    n11@{ shape: text}
    n12@{ shape: text}
    n13@{ shape: text}
