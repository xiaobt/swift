add_swift_library(swiftSema
  CodeSynthesis.cpp
  Constraint.cpp
  ConstraintGraph.cpp
  ConstraintLocator.cpp
  ConstraintSystem.cpp
  CSApply.cpp
  CSDiag.cpp
  CSGen.cpp
  CSRanking.cpp
  CSSimplify.cpp
  CSSolver.cpp
  NameBinding.cpp
  SourceLoader.cpp
  DerivedConformances.cpp
  DerivedConformanceEquatableHashable.cpp
  DerivedConformanceErrorType.cpp
  DerivedConformanceRawRepresentable.cpp
  IterativeTypeChecker.cpp
  ITCDecl.cpp
  ITCNameLookup.cpp
  ITCType.cpp
  MiscDiagnostics.cpp
  OverloadChoice.cpp
  PlaygroundTransform.cpp
  TypeChecker.cpp
  TypeCheckAttr.cpp
  TypeCheckConstraints.cpp
  TypeCheckError.cpp
  TypeCheckExpr.cpp
  TypeCheckDecl.cpp
  TypeCheckGeneric.cpp
  TypeCheckNameLookup.cpp
  TypeCheckPattern.cpp
  TypeCheckProtocol.cpp
  TypeCheckREPL.cpp
  TypeCheckRequest.cpp
  TypeCheckStmt.cpp
  TypeCheckType.cpp
  LINK_LIBRARIES
    swiftParse
    swiftAST)

