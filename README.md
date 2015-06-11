# wordpress_on_SAE
SAE(http://sae.sina.com.cn/) is a platform from Sina which may support PHP environments incloud. This project would allow user to install a wordpress instance in SAE.

Some changes were made:
- Stroage support: form local disk to SAE Storage service
- Disable update checker: All application codes in SAE are read only, so the feature is usless for SAE.
- Memcache service: Default eable memcahce service from SAE.
