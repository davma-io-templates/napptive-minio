# davma.io MINIO

> This application is for development only, it is strongly recommended not to use it in production environments.

MinIO offers high-performance, S3 compatible object storage.

## How to access to MINIO

Once the application has been deployed, open the public endpoint navigating through the web UI to select the application, selecting the wordpress component, and clicking on the associated Endpoint. Alternatively with the CLI use:

```
playground apps open davmaio-minio
```

The davmaio-minio instance automatically gets a public URL in the form of:

```
https://davmaio-minio-<code>.apps.playground.napptive.dev
```

## Admin area

To access the admin dashboard  URL:

```
https://davmaio-minio-<active-namespace>.apps.playground.napptive.dev/login
```

The default credentials are:

* User: davma-minio
* Password: davma-minio@

**Note**: Please remember to change the user/password for the instance.
To change credentials
```
https://davmaio-minio-<active-namespace>.apps.playground.napptive.dev/identity/account
```

## References
* https://min.io/
* https://docs.min.io/minio/baremetal/console/minio-console.html/










<!--    

        playground login --patFile D:/Github/no-git/napptive-cli/test_pat.dat
        kubectl --kubeconfig napptive-cli/napptive-kubeconfig create -f napptive-minio/ 

        playground catalog push davma-io/MINIO:v1.0 napptive-minio/
        playground catalog remove davma-io/MINIO:v1.
        
-->