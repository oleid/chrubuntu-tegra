##Install APC-branded Chrubuntu on Acer Chromebook CB5-311 for on-site CUDA trainings

Based on work of arm000 found [here](http://www.reddit.com/r/chrubuntu/comments/2hhb31/chrubuntu_on_acer_chromebook_13/)

### Instructions

1. Turn chromebook into developer mode:

2. Switch to developer terminal

3. Download and execute the Chrubuntu installation script

4. Redownload and re-run Chrubuntu instllation script after reboot

5. After successfully entering Chrubuntu, reboot into ChromeOS and set Chrubuntu as permanent primary boot option:

```
sudo cgpt add -i 6 -P 5 -S 1
```

To switch back the primary boot option to ChromeOS:


