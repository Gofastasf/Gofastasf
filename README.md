## Recent Contributions  

- **Terraform** – Replace custom inode-based file comparison with `os.SameFile`. [PR](https://github.com/hashicorp/terraform/pull/36562)  
- **Age** – Replace manual slice management with `bytes.Buffer` in `Writer`. [PR](https://github.com/FiloSottile/age/pull/619)  
- **Grafana** – Fix `Lstat` call and symlink permission. [PR](https://github.com/grafana/grafana/pull/100319)  
- **Kubernetes** – Avoid extra `stat` call, enhanced path handling, and improved performance. [PR](https://github.com/kubernetes/kubernetes/pull/129944)  
- **Azure-Go-SDK** – Made it OS compatible. [PR](https://github.com/Azure/azure-sdk-for-go/pull/24040)  
- **AWS-Go-SDK** – Optimize directory traversal. [PR](https://github.com/aws/aws-sdk-go-v2/pull/2970)  
- **Go Cloud** – Fix URL scheme handling case-insensitive. [PR](https://github.com/google/go-cloud/pull/3521)  
- **Milvus** – Avoid extra `stat` call. [PR](https://github.com/milvus-io/milvus/pull/39623)  
- **CockroachDB** – Avoid sys calls on every traversal to improve performance. [PR](https://github.com/cockroachdb/cockroach/pull/139108)  
- **Go-Hardware-Inspection-Library** – Avoid TOCTOU and improved logic. [PR](https://github.com/jaypipes/ghw/pull/400)  
- **Syzkaller** – Avoid `os.Lstat` calls on every traversal. [PR](https://github.com/google/syzkaller/pull/5724)  
- **Opengist** – Replace `path.Join` with `filepath.Join` for file system paths. [PR](https://github.com/thomiceli/opengist/pull/414)  

  






