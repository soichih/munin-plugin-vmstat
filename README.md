# munin-plugin-vmstat

## Installation

Git clone somewhere.. then create a symlink in /etc/munin/plugins

```
cd /etc/munin/plugins
ln -s /home/hayashis/git/munin-plugin-vmstat/vmstat vmstat 
```
(adjust the location)

## Configuration

Add your configuration in /etc/munin/plugin-conf.d/vmstat and specify parameters that you want to monitor

```
[dirty]
env.params "nr_dirty,nr_writeback,nr_writeback_temp"
```

