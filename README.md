# fluentd-aggregator

<aside>
👉 로그를 순차적으로 접근하면 문제가 생기기 않지만 동시다발적으로 로그가 발생한 경우에는 Elasticsearch가 모든 트래픽을 감당해야하는 문제가 발생합니다. 이를 해결하기 위해 **Aggregator**를 배치하여 트래픽으로 인한 ES의 부담을 감소 시킬 수 있습니다.
</aside>

### 전반적인 구조도
![fluentd-aggregator](https://github.com/user-attachments/assets/f56e8cd2-ce9f-4b6c-94b0-031f2e58bf32)
