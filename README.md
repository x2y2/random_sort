#!/usr/bin/python
#encoding: utf-8
#-*- coding: utf8 -*-
import random

def random_sort(n):
  return sorted([random.randint(1,n) for _ in range(n)])

if __name__ == '__main__':
  print random_sort(100)
