# ArabicOrDateToDateTime
Change most time string('مايو ٢٥ - ٢٠٢٢','2022-05-24T12:39:00.000+0400'.....) to datetime format e.g  datetime.datetime(2022, 5, 22, 15, 57)
import the timer module and use time_type method eg:


from .timer import time_type

date_time_str = '23 مايو 2022 - 11:32 بتوقيت أبوظبي'
date = time_type(date_time_str)
