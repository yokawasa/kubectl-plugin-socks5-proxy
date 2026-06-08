# Change Log

All notable changes to the "kubectl-plugin-socks5-proxy" extension will be documented in this file.

## v1.3.0
- Fix compatibility with newer `serjs/go-socks5-proxy` images by setting `REQUIRE_AUTH=false` by default in [#11](https://github.com/yokawasa/kubectl-plugin-socks5-proxy/pull/11)
- Add `--proxy-user` and `--proxy-password` options to enable SOCKS5 authentication explicitly in [#11](https://github.com/yokawasa/kubectl-plugin-socks5-proxy/pull/11)

## v1.2.0

- OpenShift support + default namespace by [@domq](https://github.com/domq) in [#8](https://github.com/yokawasa/kubectl-plugin-socks5-proxy/pull/8)
- fix(namespace): default proxy namespace to default when unset by [@yokawasa](https://github.com/yokawasa) in [#10](https://github.com/yokawasa/kubectl-plugin-socks5-proxy/pull/10)

## v1.1.0
- Add option for a custom podname by [@oscrx](https://github.com/oscrx) in [#6](https://github.com/yokawasa/kubectl-plugin-socks5-proxy/pull/6)

## v1.0.2
- Add param to set image by [@guai](https://github.com/guai) in [#1](https://github.com/yokawasa/kubectl-plugin-socks5-proxy/issues/1)

## v1.0.1

- Added helping message to be shown in starting the proxy

## v1.0.0

- Initial release
