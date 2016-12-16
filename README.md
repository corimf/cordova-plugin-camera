<!---
 license: Licensed to the Apache Software Foundation (ASF) under one
         or more contributor license agreements.  See the NOTICE file
         distributed with this work for additional information
         regarding copyright ownership.  The ASF licenses this file
         to you under the Apache License, Version 2.0 (the
         "License"); you may not use this file except in compliance
         with the License.  You may obtain a copy of the License at

           http://www.apache.org/licenses/LICENSE-2.0

         Unless required by applicable law or agreed to in writing,
         software distributed under the License is distributed on an
         "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
         KIND, either express or implied.  See the License for the
         specific language governing permissions and limitations
         under the License.
-->

# org.apache.cordova.camera

Plugin documentation: [doc/index.md](doc/index.md)

For Android, after installing the camera plugin, replace "${applicationId}" from the android:authorities attribute with your package ID in AndroidManifest.xml. Do NOT replace the ".provider" portion. That will still be the suffix of your package ID for this attribute. 

ex.

    <provider android:name="android.support.v4.content.FileProvider" android:authorities="com.example.provider" android:exported="false" android:grantUriPermissions="true" >
        <meta-data android:name="android.support.FILE_PROVIDER_PATHS" android:resource="@xml/provider_paths"/>
    </provider>
