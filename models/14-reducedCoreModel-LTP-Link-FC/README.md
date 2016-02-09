# Reduced Core Model  
For the second ONF MWTN PoC the ONF Core Model 1.1 is reduced to focus on the important ObjectClases and to avoid unnecessary (less important) error analysis.

## Status
Ongoing: Generated YANG files are not valid according to pyang 1.6.
The reason might be cross references within the CoreModel.uml.

## Changes made on ONF Core Model 1.1
- remove package CoreModel::ExplanatoryFiguresUsedIndDocumentsAndSlides
- remove package CoreModel::CoreModelEnhancements
- remove package CoreModel::CoreNetworkModule::TypeDefinitions::TopologyPacs
- remove package CoreModel::CoreNetworkModule::ObjectClasses::TopologyPacs
- remove package CoreModel::CoreNetworkModule::Diagrams::TopologyPacs
- remove obsolete type definition CoreModel::CoreNetworkModule::TypeDefinitions::OperationalState
- remove obsolete type definition CoreModel::CoreNetworkModule::TypeDefinitions::Directionality
- remove obsolete property CoreModel::CoreNetworkModule::ObjectClasses::NetworkElement::_ltppList
- remove obsolete property CoreModel::CoreNetworkModule::ObjectClasses::LinkPort::_ltpp
- define type for CoreModel::CoreNetworkModule::ObjectClasses::LayerProtocol::terminationState - set to Boolean
- define type for CoreModel::CoreNetworkModule::ObjectClasses::LayerProtocol::configuredClientCapacity - set to String
