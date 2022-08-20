## NetworkBehaviour

### OnEnableClient() / OnDisableClient()
Will be called if the NetworkBehaviour gets "visible" or "hidden" on the client or host.
If an InterestManagement is used, this callbacks will also be called if the NetworkBehaviour gets visible or hidden on the client/host.
OnDisableClient will also be called when the object gets destroyed on the server and is visible to an client or the host