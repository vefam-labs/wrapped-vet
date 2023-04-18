# Wrapped VET

Wrapped VET(WVET) is a VIP-180 standard token which 1:1 pegs VET.

WVET is a fork of VVET that will have the benefit of ensuring DThorSwap LPs receive their fair share of VTHO generated. The contracts have a `recoverToken` method that allows the `owner` to move any VIP-180 tokens out of the contract. This ability does not compramise the security of the underlying VET. The ability to move VIP-180s will enable the distribution of VTHO to LPs that otherwise might have been stuck, or stolen by frontrunners via the `skim` method. Initially, the VeFam team will be entrusted to distribute the `VTHO`, however, `owner` can always be changed to a trustless claim manager contract (more dev work than a centralized solution).


## Credits

[WETH9](https://github.com/gnosis/canonical-weth/commit/0dd1ea3e295eef916d0c6223ec63141137d22d67)


## Deployed contract addresses

| Network |                  Address                   |
| ------- | ------------------------------------------ |
| Mainnet | [0xb9Dfd9eAEeEdAbeB3ad41F6a88474D4a43A2307D](https://explore.vechain.org/accounts/0xb9Dfd9eAEeEdAbeB3ad41F6a88474D4a43A2307D) |
| Testnet | [0x47a7A149E22f1556de85F9144332dE45b371Be5F](https://explore-testnet.vechain.org/accounts/0x47a7A149E22f1556de85F9144332dE45b371Be5F) |



## Disclaimer
Redistributions of source code must retain this list of conditions and the following disclaimer.

Neither the name of VeFam (VeFam Labs) nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS “AS IS” AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
