# Contoso Cluster Ops

これはAzure ArcでGitOpsを行うためのサンプルです。

<!-- - [namespaces](./namespaces): creates three namespaces for the cluster: `itops`, `team-a`, and `team-b`, these namespaces are managed by the I -->
- [namespaces](./ namespaces): クラスターに3つの名前空間を作成します `itops`,` team-a`, `team-b`
<!-- - [cluster-apps](./cluster-apps): contains an application deployed by an IT operator, e.g. common monitoring or logging agent -->
-[cluster-apps](./cluster-apps): IT管理者によってデプロイされたアプリケーション(監視-ログエージェントなど)が含まれています。
<!-- - [team-a](./team-a): contains a ConfigMap produced by IT operator to communicate some configuration to an application team -->
-[team-a](./team-a): いくつかの構成をアプリケーションチームに展開するため、IT管理者が作成したConfigMapが含まれています
