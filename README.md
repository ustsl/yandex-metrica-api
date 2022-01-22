Python script for working with the API of the analytics service from Yandex Metrika.

The script formalizes the call to the API, receives data in several steps, and collects data in JSON format.

<h2>#Example</h2>

"""<br>
dimensions = ['ym:s:startOfMonth', 'ym:s:firstVisitDate']<br>
metrics = ['ym:s:visits', 'ym:s:pageDepth', 'ym:s:avgVisitDurationSeconds']<br>
date = ['2021-10-01', '2021-12-05']<br>
preset = [dimensions, metrics]<br>
params = {'date': date, 'preset': preset, 'filters': None}<br>
token = 'token'<br>
counter = 'yandex metrica counter'<br>
"""
