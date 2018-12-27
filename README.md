# myDischarge stacktrace
Get this exception text: System.ServiceModel.FaultException: Badly formed SOAP Message

Server stack trace: 
   at System.ServiceModel.Channels.ServiceChannel.HandleReply(ProxyOperationRuntime operation, ProxyRpc& rpc)
   at System.ServiceModel.Channels.ServiceChannel.Call(String action, Boolean oneway, ProxyOperationRuntime operation, Object[] ins, Object[] outs, TimeSpan timeout)
   at System.ServiceModel.Channels.ServiceChannelProxy.InvokeService(IMethodCallMessage methodCall, ProxyOperationRuntime operation)
   at System.ServiceModel.Channels.ServiceChannelProxy.Invoke(IMessage message)

Exception rethrown at [0]: 
   at System.Runtime.Remoting.Proxies.RealProxy.HandleReturnMessage(IMessage reqMsg, IMessage retMsg)
   at System.Runtime.Remoting.Proxies.RealProxy.PrivateInvoke(MessageData& msgData, Int32 type)
   at myAvimport.NTSTWEBSRV_ClientDischarge_SANDBOX.ClientDischargeSoap.DischargeClient(DischargeClientRequest request)
   at myAvimport.NTSTWEBSRV_ClientDischarge_SANDBOX.ClientDischargeSoapClient.myAvimport.NTSTWEBSRV_ClientDischarge_SANDBOX.ClientDischargeSoap.DischargeClient(DischargeClientRequest request) in C:\Users\ckennedy\Desktop\MyAvimport\myAvimport-SBOX\myAvimport\Connected Services\NTSTWEBSRV_ClientDischarge_SANDBOX\Reference.cs:line 3542
   at myAvimport.NTSTWEBSRV_ClientDischarge_SANDBOX.ClientDischargeSoapClient.DischargeClient(String SystemCode, String UserName, String Password, ClientDischargeObject ClientDischargeInfo, String ClientID, String EpisodeNumber) 
in C:\Users\ckennedy\Desktop\MyAvimport\myAvimport-SBOX\myAvimport\Connected Services\NTSTWEBSRV_ClientDischarge_SANDBOX\Reference.cs:line 3554
   at myAvimport.ClientDischarge.DischargeClient(String systemCode, String username, String password, ClientDischargeObject clientDischargeObject, String clientID, Boolean testMode) 
in C:\Users\ckennedy\Desktop\MyAvimport\myAvimport-SBOX\myAvimport\ClientDischarge.cs:line 189
   at myAvimport.ClientDischarge.Import(Dictionary`2 clientDischargeObjects, String systemCode, String username, String password, Boolean testMode, Boolean throttleImport) 
in C:\Users\ckennedy\Desktop\MyAvimport\myAvimport-SBOX\myAvimport\ClientDischarge.cs:line 147
   at myAvimport.MyAvimport.BtnImport_Click(Object sender, EventArgs e) 
in C:\Users\ckennedy\Desktop\MyAvimport\myAvimport-SBOX\myAvimport\MyAvimport.cs:line 67
   at System.Windows.Forms.Control.OnClick(EventArgs e)
   at ...

