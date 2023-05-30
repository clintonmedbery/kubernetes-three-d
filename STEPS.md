Prerequisites:

For these steps, I am going to assume you know the ins and outs of NPM and have some amount of experience in kubernetes/docker. To get us going locally, I am going to be using `kind`, but you can use any kubernetes cluster you want. Let's create a cluster.

## Install Kind

https://kind.sigs.k8s.io/docs/user/quick-start/

## Creating a Kind Cluster

To create a Kind cluster, follow these steps:

1. Open a terminal or command prompt.

2. Run the following command to create a Kind cluster:
   ```bash
   kind create cluster

## Walkthrough
Run
`npm create vite@latest`

Choose an app name.
Choose React.
Choose Typescript.

You should see something like the following:
![image](https://github.com/clintonmedbery/kubernetes-three-d/assets/7118459/6d87ca23-378d-471c-8836-f079f9b7abfb)

Next install the kubernetes javascript client:
`npm install -S @kubernetes/client-node`

Install node polyfills:
`npm install --save-dev vite-plugin-node-polyfills`




