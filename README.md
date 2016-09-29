# RxFilters

This is a first iteration of a set of high pass filters for a receiver. The filters are to be used in conjunction with the transmit low pass filters to form a bandpass filter which can be of variable width depending on the HP/LP combination selected. The advantage of this is that the Rx bandwidth can be wide (up to the Tx LP frequency) to enable skimming of frequencies up to the Tx frequency. I will be looking at diode switching of the filters in the future as this will give the option of developing smart filter switching to allow cross band operation etc. The receive can be a band set formed from a HP/LP combination and then when going to Tx the LP filter can be switched to match the Tx frequency and restored on receive.

This version is Relays only.

Notes:
The 1.8 MHz High Pass filter is in circuit by default all the time. In practise the broadcast signals are so strong that they can be received with the filter in. If full sensitivity operation in the broadcast and LF bands is desired then the filter is switched out and any appropriate filter switched in. Also with Hermes-Light the LNA gain can be reduced until clipping stops.
