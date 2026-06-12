# GL005-fw-policy

FortiGate 200F demo firewall policy repository for education and demonstration purposes.

## Demo layout

The repository now contains a mock FortiGate environment under `/fortigate-200f-demo` split by configuration type so the snippets can be reviewed or imported in a logical order:

- `/home/runner/work/GL005-fw-policy/GL005-fw-policy/gar-rock/GL005-fw-policy/fortigate-200f-demo/config/system-global.conf`
- `/home/runner/work/GL005-fw-policy/GL005-fw-policy/gar-rock/GL005-fw-policy/fortigate-200f-demo/network/interfaces.conf`
- `/home/runner/work/GL005-fw-policy/GL005-fw-policy/gar-rock/GL005-fw-policy/fortigate-200f-demo/network/static-routes.conf`
- `/home/runner/work/GL005-fw-policy/GL005-fw-policy/gar-rock/GL005-fw-policy/fortigate-200f-demo/network/zones.conf`
- `/home/runner/work/GL005-fw-policy/GL005-fw-policy/gar-rock/GL005-fw-policy/fortigate-200f-demo/objects-db/address-objects.conf`
- `/home/runner/work/GL005-fw-policy/GL005-fw-policy/gar-rock/GL005-fw-policy/fortigate-200f-demo/objects-db/address-groups.conf`
- `/home/runner/work/GL005-fw-policy/GL005-fw-policy/gar-rock/GL005-fw-policy/fortigate-200f-demo/objects-db/service-objects.conf`
- `/home/runner/work/GL005-fw-policy/GL005-fw-policy/gar-rock/GL005-fw-policy/fortigate-200f-demo/policies/firewall-policies.conf`

## What is included

- Mock Internet egress, business, OT/process, and DMZ zones
- Mock physical and VLAN interfaces with RFC 5737 and private demo addressing
- Address objects, host objects, IP ranges, FQDN objects, and address groups
- Custom service objects and service groups for common enterprise and OT flows
- More than 200 mock firewall policies to demonstrate internet egress, east-west, shared-services, OT, partner, and DMZ access patterns

All values are intentionally fictional and safe for demonstration use.
