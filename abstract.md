# Abstract

Azure cloud environments contain critical resources such as virtual machines, storage accounts, and virtual networks that may be accidentally deleted or modified by users or administrators. This project, titled **“Azure Resource Locks and Deployment Safety Controls,”** focuses on improving the safety and governance of Azure resources by implementing Resource Locks.

The project uses Azure Resource Locks, primarily the **CanNotDelete** lock, to prevent accidental deletion of critical resources. A controlled change-management workflow is also designed in which authorized administrators can temporarily remove the lock, perform approved changes, validate the resources, and reapply the protection.

The proposed solution demonstrates how Azure-native governance mechanisms can provide an additional layer of protection for cloud resources and support safer resource management and deployment practices.
