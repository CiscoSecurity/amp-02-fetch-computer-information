[![Gitter chat](https://img.shields.io/badge/gitter-join%20chat-brightgreen.svg)](https://gitter.im/CiscoSecurity/AMP-for-Endpoints "Gitter chat")

### AMP for Endpoint Fetch Computer Information:

These scripts provide examples for parsing specific elements from the JSON returned by the /computers endpoint. Some elements that examples are provided for include:
- connector GUIDs
- hostnames of computers
- MAC addresses

### Before using you must update the following:
- client_id
- api_key

### Usage:
```
python 01_get_guids.py
```

### Example script output:
```
bde82e9f-dae3-4891-8730-f75a8ebee4dc
364dbabf-209e-44f8-9447-be0ed0a6d3b5
43ea5bb6-a4ec-48fa-876c-59cc304fda17
b0a69c58-be3a-4549-9c60-1d2fa3031229
13de840a-3577-41b3-8930-1917ca87ceda
14dcfce3-9663-434d-9beb-c8836de035ce
93252a58-6d27-4687-b5a5-4e32e54cc166
11ce61b5-bf3c-43f6-8d63-ee20a986a420
43af918c-dc5e-4a64-ad17-63772c695e64
9fc87138-e65a-48cf-85c2-f5b8834e2109
d2721a44-3795-4138-a73a-f36e6d8b0201
```
