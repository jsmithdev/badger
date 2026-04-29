# badger

[![WIZ Cloud Security](https://img.shields.io/badge/WIZ-Not%20Configured-lightgrey)](https://www.wiz.io/)

To display live WIZ status in this README, replace the badge URL above with a Shields endpoint badge backed by a JSON endpoint you control, for example:

[![WIZ Cloud Security](https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fjsmithdev%2Fbadger%2Frefs%2Fheads%2Fmain%2Fsecure.json)](https://app.wiz.io/)


Expected endpoint payload format:

```json
{
	"schemaVersion": 1,
	"label": "WIZ",
	"message": "secure",
	"color": "brightgreen"
}
```
