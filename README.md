# WeeWX-ws23xx.py-driver
The original wx23xx.py driver for WeeWX wouldn't report 0 mph winds by design. This is incorrect. 
Wind speed should always be reported even if it is zero along with the gusts. I updated the driver to always report wind speed. 
