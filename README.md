# Wazuh Findings Exporter
Scripts written in Python to export all Wazuh vulnerabilities into a .JSON file.

Feel free to provide PRs and help to improve it.

## Attribution

The file `get_vulnerabilities_updated.py` was originally written by **Leon** from the Wazuh Support Team and is licensed under the *GNU General Public License v2.0*.

The file `DD_get_vulnerabilities.py` is a modified version of the original script written by @9alexx3, adapted to export vulnerabilities to DefectDojo. It is distributed under the same license as the original.

## Prerrequesites:

Install requests and urllib3 dependences:
```bash
pip3 install requests urllib3
```

## Usage:

The same instructions are applicable to both scripts.

```bash
python3 DD_get_vulnerabilities.py --es-url YOUR_ELASTICSEARCH_INSTANCE --es-user ELASTICSEARCH_USER --es-pass ELASTICSEARCH_PASSWORD [--ca-cert CA_CERT] [--output-dir OUTPUT_DIR] [--index INDEX] [-s MAX_SIZE]
```
