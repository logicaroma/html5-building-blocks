These events are fired on `[[audio]]` and `[[video]]` elements.

####[[abort]]
Fires when playback is aborted; for example, if the media is playing and is restarted from the beginning, this event is sent.

####[[canplay]]
Fires when enough data is available that the media can be played, at least for a couple of frames.  This corresponds to the CAN_PLAY readyState.

####[[canplaythrough]]
Fires when the ready state changes to CAN_PLAY_THROUGH, indicating that the entire media can be played without interruption, assuming the download rate remains at least at the current level.

####[[canshowcurrentframe]]
The current frame has loaded and can be presented.  This corresponds to the CAN_SHOW_CURRENT_FRAME readyState.

####[[dataunavailable]]
Fires when the ready state changes to DATA_UNAVAILABLE.

####[[durationchange]]
The metadata has loaded or changed, indicating a change in duration of the media.  This is sent, for example, when the media has loaded enough that the duration is known.

####[[emptied]]
The media has become empty; for example, this event is sent if the media has already been loaded (or partially loaded), and the load() method is called to reload it.

####[[empty]]
Fires when an error occurs and the media is empty.

####[[ended]]
Fires when playback completes.

####[[error]]
Fires when an error occurs. The media element's error attribute contains more information. See Error handling for details.

####[[loadeddata]]
The first frame of the media has finished loading.

####[[loadedmetadata]]
The media's metadata has finished loading; all attributes now contain as much useful information as they're going to.

####[[loadstart]]
Fires when loading of the media begins.

####[[pause]]
Fires when playback is paused.

####[[play]]
Fires when playback of the media starts after having been paused; that is, when playback is resumed after a prior pause event.

####[[playing]]
Fires when the media begins to play (either for the first time, after having been paused, or after ending and then restarting).

####[[progress]]
Sent periodically to inform interested parties of progress downloading the media. Information about the current amount of the media that has been downloaded is available in the media element's buffered attribute.

####[[ratechange]]
Fires when the playback speed changes.

####[[seeked]]
Fires when a seek operation completes.

####[[seeking]]
Fires when a seek operation begins.

####[[timeupdate]]
The time indicated by the media element's currentTime attribute has changed.

####[[volumechange]]
Fires when the media element's volume changes (both when the volume is set and when the muted attribute is changed).

####[[waiting]]
Fires when the requested operation (such as playback) is delayed pending the completion of another operation (such as a seek).