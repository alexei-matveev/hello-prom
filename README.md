# Hello Prom

Use e.g. [k3s](https://github.com/rancher/k3s) as no bullsh*t
Kubernetes.

    kubectl create namespace hello-prom
    kubectl config set-context --current --namespace=hello-prom
    kubectl apply -k ./k3s

Then point your browser to [URL](http://prometheus.localhost).

## License

Copyright © 2019 Alexei Matveev <alexei.matveev@gmail.com>

This program and the accompanying materials are made available under the
terms of the Eclipse Public License 2.0 which is available at
http://www.eclipse.org/legal/epl-2.0.

This Source Code may also be made available under the following Secondary
Licenses when the conditions for such availability set forth in the Eclipse
Public License, v. 2.0 are satisfied: GNU General Public License as published by
the Free Software Foundation, either version 2 of the License, or (at your
option) any later version, with the GNU Classpath Exception which is available
at https://www.gnu.org/software/classpath/license.html.
