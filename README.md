# ce340-final-assignment-secure-authentication-protocol-sap-solved
**TO GET THIS SOLUTION VISIT:** [CE340 Final Assignment-Secure Authentication Protocol (SAP) Solved](https://www.ankitcodinghub.com/product/final-assignment-ce-340-cryptography-network-security-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;113002&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CE340 Final Assignment-Secure Authentication Protocol (SAP) Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Title: Implementation of Secure Authentication Protocol (SAP)

Max # of project members is 2

Write a set of Sage/Python functions in a python script, which will implement an authentication system with digital signature shown in the following figure. When running the script it will read the source’s ID from ID.txt file, which contains full citizen registration data (kimlik bilgilerinin tamamı). Please, note that KH function for the source entity is KH = XOR(KRSRC, KUDST) and for the destination it is KH = XOR(KRDST, KUSRC).

A) Function list for the source:

1. H = H(ID): Computes and returns the hash value of the source node.

2. S = E(H, KH): Encrypts and returns the hash value, which is the signature (S) of the source. Note that the encryption is symmetric key.

3. CC = conc(X,Y): Concatenates X and Y and returns the result as CC.

4. KS: Generate a large integer denoting the session key. The key KS must have at least 10 digits.

5. Z=signID(conc [E(conc(ID,S), KS )), E(KS, KUDST)]).

6. Boolean send(Z, dest_IP): Sends the signed ID to the destination and returns True if successful otherwise returns False.

B) You will define the function list for the destination from the block diagram given above, and implement them as appropriate. For example, the verification function is something like

Verify(Hash_sent, Hash_computed): This will compare these (strings) and print “verified” if the input parameters are equal, otherwise it will print “Verification failed”

The report should prove (by screenshot) and explain the verification of the authentication of the source entity done by the destination. You will deliver at least two tests with 2 different IDs and different also with different Keys.

For the public key cryptography you need to use RSA system, which is explained in the slide set (on BB) named as public_key_crypto.pptx.

What to deliver?

1) Execution trace (e.g., screenshots) of each operation
