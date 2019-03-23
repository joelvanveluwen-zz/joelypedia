# Quantified self

I've had a long running interest in collecting and analysing my own personal data. I'm currently building a centralised and self-hosted dashboard to track insights, contextualise my own life and drive changes in behaviour. 

## Gear

For weight I'm using a **Withings WS-30** I bought in 2014, I've got ~daily data from 2014 around my weight levels and the thing is still running. 

I've recently \(2019\) acquired a **Withing Blood Pressure Monitor** which I use for daily ****systolic and diastolic measurement. 

I have a _sad_ Misift Shine that does some basic activity monitoring. 

I'm building a polysomnography \(PSG\) 'sleep study' rig for more advanced sleep measurement and understanding. I'm particularly keen to use machine learning to score quality of sleep and see if I can make lifestyle changes to improve sleep quality. The rig is made mostly from equipment by [Open BCI](http://openbci.com).

## Current architecture

As it stands I'm still designing the architecture of this quantified self-effort. Withings and Misfit data will pipe easily via API \([especially with something like this](https://github.com/openmhealth/shimmer)\) but the large challenge is handling the gigabytes of brainwave data that comes from the PSG collection. I'm likely going to see if I can score it locally or via edge computing, otherwise I'll see what cloud options will work before it gets unified with the other data in one front end. 

