# grafana-message-templates

Reference links

- https://faun.pub/overview-of-grafana-alerting-and-message-templating-for-slack-6bb740ec44af
- https://docs.aws.amazon.com/grafana/latest/userguide/alert-message-templates.html
- https://grafana.com/docs/grafana/latest/alerting/fundamentals/annotation-label/variables-label-annotation/


We can add the required information in alert Summary

```
PVC : {{ $labels.persistentvolumeclaim }} 
Namespace: {{ $labels.namespace}}
Usage : {{ $values.B }}

```
<img width="884" alt="image" src="https://user-images.githubusercontent.com/81069965/210045365-b0422313-8798-479f-8bca-545d428ea766.png">

