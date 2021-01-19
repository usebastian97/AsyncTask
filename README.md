# AsyncTask-(Java Example) [![Build Status](https://img.shields.io/badge/made%20by-Sebastian%20Utoiu-brightgreen)](https://img.shields.io/badge/made%20by-Sebastian%20Utoiu-brightgreen)


## Info

AsyncTask was intended to enable proper and easy use of the UI thread. However, the most common use case was for integrating into UI, and that would cause Context leaks, missed callbacks, or crashes on configuration changes. It also has inconsistent behavior on different versions of the platform, swallows exceptions from doInBackground, and does not provide much utility over using Executors directly..

AsyncTask is designed to be a helper class around Thread and Handler and does not constitute a generic threading framework. AsyncTasks should ideally be used for short operations (a few seconds at the most.) If you need to keep threads running for long periods of time, it is highly recommended you use the various APIs provided by the java.util.concurrent package such as Executor, ThreadPoolExecutor and FutureTask.

An asynchronous task is defined by a computation that runs on a background thread and whose result is published on the UI thread. An asynchronous task is defined by 3 generic types, called Params, Progress and Result, and 4 steps, called onPreExecute, doInBackground, onProgressUpdate and onPostExecute.


## Screenshots

![Screenshot_1611061489](https://user-images.githubusercontent.com/76481422/105048742-8e988b00-5a74-11eb-9354-844498616321.png) ![Screenshot_1611061492](https://user-images.githubusercontent.com/76481422/105048753-90624e80-5a74-11eb-9623-c5feea32c5a6.png)
