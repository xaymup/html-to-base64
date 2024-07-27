A simple JS code for converting HTML to base64.

You can try it out by copying the following into your browser's address bar:

  data:text/html;base64,CjwhRE9DVFlQRSBodG1sPgo8aHRtbCBsYW5nPSJlbiI+CjxoZWFkPgogICAgPG1ldGEgY2hhcnNldD0iVVRGLTgiPgogICAgPG1ldGEgbmFtZT0idmlld3BvcnQiIGNvbnRlbnQ9IndpZHRoPWRldmljZS13aWR0aCwgaW5pdGlhbC1zY2FsZT0xLjAiPgogICAgPHRpdGxlPkhUTUwgdG8gQmFzZTY0IENvbnZlcnRlcjwvdGl0bGU+CiAgICA8c3R5bGU+CiAgICAgICAgYm9keSB7CiAgICAgICAgICAgIGZvbnQtZmFtaWx5OiBBcmlhbCwgc2Fucy1zZXJpZjsKICAgICAgICAgICAgcGFkZGluZzogMjBweDsKICAgICAgICB9CiAgICAgICAgdGV4dGFyZWEgewogICAgICAgICAgICB3aWR0aDogMTAwJTsKICAgICAgICAgICAgaGVpZ2h0OiAxNTBweDsKICAgICAgICAgICAgbWFyZ2luLWJvdHRvbTogMTBweDsKICAgICAgICB9CiAgICAgICAgYnV0dG9uIHsKICAgICAgICAgICAgZGlzcGxheTogYmxvY2s7CiAgICAgICAgICAgIG1hcmdpbi10b3A6IDEwcHg7CiAgICAgICAgfQogICAgICAgICNvdXRwdXQgewogICAgICAgICAgICBtYXJnaW4tdG9wOiAyMHB4OwogICAgICAgICAgICBwYWRkaW5nOiAxMHB4OwogICAgICAgICAgICBib3JkZXI6IDFweCBzb2xpZCAjZGRkOwogICAgICAgICAgICBiYWNrZ3JvdW5kLWNvbG9yOiAjZjlmOWY5OwogICAgICAgIH0KICAgIDwvc3R5bGU+CjwvaGVhZD4KPGJvZHk+CiAgICA8aDE+SFRNTCB0byBCYXNlNjQgQ29udmVydGVyPC9oMT4KICAgIDx0ZXh0YXJlYSBpZD0iaHRtbC1pbnB1dCIgcGxhY2Vob2xkZXI9IkVudGVyIHlvdXIgSFRNTCBoZXJlLi4uIj48L3RleHRhcmVhPgogICAgPGJ1dHRvbiBvbmNsaWNrPSJjb252ZXJ0VG9CYXNlNjQoKSI+Q29udmVydCB0byBCYXNlNjQ8L2J1dHRvbj4KICAgIDxkaXYgaWQ9Im91dHB1dCI+CiAgICAgICAgPHRleHRhcmVhIGlkPSJiYXNlNjQtb3V0cHV0IiByZWFkb25seSBwbGFjZWhvbGRlcj0iQmFzZTY0IGVuY29kZWQgc3RyaW5nIHdpbGwgYXBwZWFyIGhlcmUuLi4iPjwvdGV4dGFyZWE+CiAgICAgICAgPGJ1dHRvbiBvbmNsaWNrPSJjb3B5VG9DbGlwYm9hcmQoKSI+Q29weSB0byBDbGlwYm9hcmQ8L2J1dHRvbj4KICAgIDwvZGl2PgoKICAgIDxzY3JpcHQ+CiAgICAgICAgZnVuY3Rpb24gY29udmVydFRvQmFzZTY0KCkgewogICAgICAgICAgICBjb25zdCBodG1sSW5wdXQgPSBkb2N1bWVudC5nZXRFbGVtZW50QnlJZCgnaHRtbC1pbnB1dCcpLnZhbHVlOwogICAgICAgICAgICBpZiAoIWh0bWxJbnB1dCkgewogICAgICAgICAgICAgICAgYWxlcnQoJ1BsZWFzZSBlbnRlciBIVE1MIHNvdXJjZSB0byBjb252ZXJ0LicpOwogICAgICAgICAgICAgICAgcmV0dXJuOwogICAgICAgICAgICB9CgogICAgICAgICAgICAvLyBFbmNvZGUgSFRNTCB0byBCYXNlNjQKICAgICAgICAgICAgY29uc3QgZW5jb2RlZEh0bWwgPSBidG9hKHVuZXNjYXBlKGVuY29kZVVSSUNvbXBvbmVudChodG1sSW5wdXQpKSk7CiAgICAgICAgICAgIGNvbnN0IGRhdGFVcmwgPSBgZGF0YTp0ZXh0L2h0bWw7YmFzZTY0LCR7ZW5jb2RlZEh0bWx9YDsKCiAgICAgICAgICAgIC8vIERpc3BsYXkgdGhlIHJlc3VsdAogICAgICAgICAgICBjb25zdCBiYXNlNjRPdXRwdXQgPSBkb2N1bWVudC5nZXRFbGVtZW50QnlJZCgnYmFzZTY0LW91dHB1dCcpOwogICAgICAgICAgICBiYXNlNjRPdXRwdXQudmFsdWUgPSBkYXRhVXJsOwogICAgICAgIH0KCiAgICAgICAgZnVuY3Rpb24gY29weVRvQ2xpcGJvYXJkKCkgewogICAgICAgICAgICBjb25zdCBiYXNlNjRPdXRwdXQgPSBkb2N1bWVudC5nZXRFbGVtZW50QnlJZCgnYmFzZTY0LW91dHB1dCcpOwogICAgICAgICAgICBiYXNlNjRPdXRwdXQuc2VsZWN0KCk7CiAgICAgICAgICAgIGRvY3VtZW50LmV4ZWNDb21tYW5kKCdjb3B5Jyk7IC8vIENvcHkgdG8gY2xpcGJvYXJkCiAgICAgICAgICAgIGFsZXJ0KCdCYXNlNjQgc3RyaW5nIGNvcGllZCB0byBjbGlwYm9hcmQhJyk7CiAgICAgICAgfQogICAgPC9zY3JpcHQ+CjwvYm9keT4KPC9odG1sPgo=
