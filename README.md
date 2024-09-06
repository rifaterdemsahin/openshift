# OpenShift YAML Templates

This project provides 20 different YAML templates in OpenShift, representing core aspects of deploying and managing applications and services within an OpenShift cluster.

---

## Table of Contents

1. [Pod Template](#1-pod-template)
2. [DeploymentConfig Template](#2-deploymentconfig-template)
3. [Service Template](#3-service-template)
4. [Route Template](#4-route-template)
5. [PersistentVolumeClaim (PVC) Template](#5-persistentvolumeclaim-pvc-template)
6. [BuildConfig Template](#6-buildconfig-template)
7. [ImageStream Template](#7-imagestream-template)
8. [CronJob Template](#8-cronjob-template)
9. [Secret Template](#9-secret-template)
10. [ConfigMap Template](#10-configmap-template)
11. [HorizontalPodAutoscaler (HPA) Template](#11-horizontalpodautoscaler-hpa-template)
12. [DaemonSet Template](#12-daemonset-template)
13. [StatefulSet Template](#13-statefulset-template)
14. [Job Template](#14-job-template)
15. [ServiceAccount Template](#15-serviceaccount-template)
16. [Role Template](#16-role-template)
17. [RoleBinding Template](#17-rolebinding-template)
18. [NetworkPolicy Template](#18-networkpolicy-template)
19. [LimitRange Template](#19-limitrange-template)
20. [ResourceQuota Template](#20-resourcequota-template)

---

## 1. Pod Template
Details on creating a basic Pod to run containers in OpenShift.

## 2. DeploymentConfig Template
Manages pod creation, scaling, and updates for applications.

## 3. Service Template
Exposes a group of Pods and makes them accessible.

## 4. Route Template
Defines how external traffic reaches services in OpenShift.

## 5. PersistentVolumeClaim (PVC) Template
Requests storage from the OpenShift cluster for persistent data.

## 6. BuildConfig Template
Defines how to build container images from source code.

## 7. ImageStream Template
Tracks image versions and manages container image updates.

## 8. CronJob Template
Runs scheduled tasks at specified intervals.

## 9. Secret Template
Stores sensitive data like passwords and API tokens.

## 10. ConfigMap Template
Stores non-sensitive configuration data for use by applications.

## 11. HorizontalPodAutoscaler (HPA) Template
Scales Pods based on CPU utilization automatically.

## 12. DaemonSet Template
Ensures all or some nodes run a copy of a specific Pod.

## 13. StatefulSet Template
Manages stateful applications and ensures ordered scaling and deployment.

## 14. Job Template
Runs a one-time task until completion.

## 15. ServiceAccount Template
Provides identity for Pods to interact with the OpenShift API.

## 16. Role Template
Defines access permissions for resources in a specific namespace.

## 17. RoleBinding Template
Grants access to users or groups for specific roles.

## 18. NetworkPolicy Template
Controls network traffic flow between Pods.

## 19. LimitRange Template
Enforces resource usage constraints for Pods in a namespace.

## 20. ResourceQuota Template
Limits resource usage in a namespace to ensure fair allocation.
