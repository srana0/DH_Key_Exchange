# DB_Key_Exchange

Let us consider the following authenticated DH key exchange protocol to establish a secret shared key in the Internet Protocol Security (IPsec) standards. The protocol for two parties, namely Alice and Bob is described below and a high-level overview is shown in Figure 1. Use the following cyclic
group of prime order q: $G=\mathbb{Z}_{P}^{*}$. 

Use the generator g of $G=\mathbb{Z}_{P}^{*}$ provided in the parameter section. Use the DSA implementation for KeyGen(), Sig(), and Verify(). You can generate a pair
of signing-and-verication keys for Alice and Bob, denoted by $(vk_{A}, sk_{A})$

# Parameters

p:= 50702342087986984684596540672785294493370824085308498450535565701730450879745310594069460940052367603038103747343106687981163754506284021184158903198888031001641800021787453760919626851704381009545624331468658731255109995186698602388616345118779571212089090418972317301933821327897539692633740906524461904910061687459642285855052275274576089050579224477511686171168825003847462222895619169935317974865296291598100558751976216418469984937110507061979400971905781410388336458908816885758419125375047408388601985300884500733923194700051030733653434466714943605845143519933901592158295809020513235827728686129856549511535000228593790299010401739984240789015389649972633253273119008010971111107028536093543116304613269438082468960788836139999390141570158208410234733780007345264440946888072018632119778442194822690635460883177965078378404035306423001560546174260935441728479454887884057082481520089810271912227350884752023760663

q:= 63762351364972653564641699529205510489263266834182771617563631363277932854227

g:= 2
