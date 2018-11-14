import psycopg2
import pandas as pd
import numpy as np
from matplotlib import pyplot as plt
%matplotlib inline
import seaborn as sns
import datetime as dt


import seaborn as sns
import datetime

from Ignore import db_cred
conn = db_cred.connect_db()
