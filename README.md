# Google Cloud Storage Bugbounty

<br>
<br>

Tool to enumerate Google Storage Buckets: https://github.com/RhinoSecurityLabs/GCPBucketBrute

<br>
#### Enumerate bucket permission: 
<br>
```
www.googleapis.com/storage/v1/b/{}/iam/testPermissions?permissions=storage.buckets.delete&permissions=storage.buckets.get&permissions=storage.buckets.getIamPolicy&permissions=storage.buckets.setIamPolicy&permissions=storage.buckets.update&permissions=storage.objects.create&permissions=storage.objects.delete&permissions=storage.objects.get&permissions=storage.objects.list&permissions=storage.objects.update
```
