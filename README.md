# ANOFlow

ANO optical flow parser module for the UART4 link.

## Required Hardware

- `ano_flow_uart`
- `ramfs`

## Constructor Arguments

- `data_topic_name`: `ano_flow_data`
- `task_stack_depth`: `1024`

## Output

- `ANOFlow::Data`

## Notes

- Parses the ANO optical-flow binary stream.
- Publishes link-health, flow velocity, altitude, IMU sideband data, and
  quaternion payloads from the sensor.
