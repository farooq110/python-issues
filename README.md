# python-issues

#2. Force Pip to Use Disk Instead of RAM (/tmp)
TMPDIR=/var/tmp pip install --no-cache-dir -r requirements.txt
This bypasses the RAM-limited /tmp and uses disk-based /var/tmp.
